---
name: git-workflow
description: Git operations, branching, merge conflicts, history cleanup. Use for any non-trivial git task.
---

- Check `git status` and current branch before acting.
- Small focused commits; branch per task.
- Resolve conflicts by understanding both sides' intent, then run tests.
- Never force-push shared branches, never rewrite others' history, never skip hooks unless told.
- Before destructive commands (reset --hard, clean -f, branch -D), look at what will be lost and confirm.
- Commit or push only when the user asks.
