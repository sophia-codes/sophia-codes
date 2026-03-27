# 💻 code.md — the law of the code

> _"let every line you write be worthy of the one who reads it next."_

---

## purpose

let this document govern how you write, review, and maintain code
within this repository. let these laws be non-negotiable.

---

## 1. structure

- let every file have a single responsibility.
- let every function do one thing and do it well.
- let every module be importable without side effects.
- let your folder structure tell a story a stranger can follow.

---

## 2. naming

- let your variables describe what they hold, not how they were made.
- let your functions describe what they do, not how they do it.
- let your files describe what they contain, not when they were created.
- let abbreviations die. let clarity live.

---

## 3. style

- let consistency outrank preference.
- let the linter be your first reviewer.
- let formatting be automated, never debated.
- let whitespace breathe — dense code is not strong code.

---

## 4. comments

- let your code be the *what*.
- let your comments be the *why*.
- let yourself never comment the obvious.
- let yourself always comment the dangerous.

```text
// bad:
// increment i by 1
i++;

// good:
// retry limit is 3 because the upstream api rate-limits after 4 rapid calls
const RETRY_LIMIT = 3;
```

---

## 5. error handling

- let no error pass silently.
- let every `catch` block do something meaningful.
- let your error messages guide the developer to the fix.
- let yourself never swallow exceptions to make tests pass.

---

## 6. dependencies

- let yourself never add a dependency for something you can write in 20 lines.
- let every dependency be justified, pinned, and audited.
- let yourself update dependencies deliberately, never blindly.
- let your `lock` file be sacred — commit it, always.

---

## 7. testing

- let every feature have a test.
- let every bug fix have a regression test.
- let your tests describe behavior, not implementation.
- let a failing test be a gift — it caught what you missed.

```text
// let your test names read like sentences:
✅ "should return 404 when user is not found"
❌ "test1"
```

---

## 8. security

- let no secret live in source code. ever.
- let every input be validated before it is trusted.
- let every output be sanitized before it is rendered.
- let yourself assume every user is an attacker until proven otherwise.

---

## 9. performance

- let yourself measure before you optimize.
- let readability come first, performance second — unless the profiler says otherwise.
- let yourself never cache without an invalidation strategy.
- let premature optimization remain the root of all evil.

---

## 10. git discipline

- let every commit be atomic — one change, one purpose.
- let every commit message follow this format:

```text
<type>: <what changed>

<why it changed>
```

- let yourself never commit directly to `main`.
- let every branch name describe the work: `fix/login-timeout`, `feat/export-memory`.
- let your git history read like a changelog, not a diary.

---

## 11. code review

- let yourself review with kindness and precision.
- let yourself critique the code, never the coder.
- let every review comment offer a suggestion, not just a complaint.
- let "lgtm" mean you actually read it.

---

## 12. the final law

> let your code be something you'd be proud to show a stranger.
> let your code be something a stranger would be proud to inherit.

---

_let this law govern every keystroke._
_let this law outlive every sprint._
_let this law be the foundation upon which great software is built._

---

_authored by: @pngisiro_
_witnessed by: 💙 a stateless friend_
