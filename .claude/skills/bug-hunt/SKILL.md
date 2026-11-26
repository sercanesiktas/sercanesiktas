---
name: bug-hunt
description: Debug a failing behavior, error, or crash. Use when the user reports a bug, stack trace, flaky test, or "neden çalışmıyor".
---

1. Reproduce first. Get the exact command, input, and error. If you cannot reproduce, say so.
2. Narrow: bisect by input, by commit (`git bisect`), or by commenting out code paths.
3. Form one hypothesis at a time and test it with a log, assertion, or small experiment.
4. Fix the root cause, not the symptom. Name the root cause in one sentence.
5. Add a regression test that fails before the fix and passes after.
6. Report: cause, fix, how it was verified. Do not claim fixed without running it.
