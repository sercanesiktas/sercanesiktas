---
name: refactor-safe
description: Restructure code without changing behavior. Use for cleanup, renames, extracting functions, removing duplication.
---

1. Confirm tests exist and pass before touching anything; add characterization tests if missing.
2. Make small steps; run tests after each.
3. Never mix refactoring with behavior changes in one commit.
4. Prefer deleting code over adding abstractions. No speculative generality.
5. Search all call sites (including tests, docs, configs) before renaming or removing.
6. Summarize what moved and confirm behavior is unchanged.
