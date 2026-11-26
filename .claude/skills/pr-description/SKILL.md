---
name: pr-description
description: Write commit messages and pull request descriptions. Use when committing, opening a PR, or summarizing a diff.
---

- Read the full diff and recent `git log` to match style.
- Commit subject: imperative, <=72 chars, says what and why. Body explains motivation, not line-by-line changes.
- PR: Summary (why), Changes (what), Testing (how verified), Risks/rollout. Follow the repo's PR template if present.
- Link issues. Call out breaking changes and migrations first.
- Never invent test results.
