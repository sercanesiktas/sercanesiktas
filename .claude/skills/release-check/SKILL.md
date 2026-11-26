---
name: release-check
description: Pre-release and pre-merge checklist. Use before shipping, tagging, or deploying.
---

- Tests, lint, type-check, and build all pass (show output).
- No debug code, TODOs that block, or committed secrets.
- Dependencies audited; lockfile updated.
- Migrations and config changes documented, with a rollback plan.
- Changelog and version bumped; docs updated.
- Smoke-test the real artifact, not just unit tests.
- Report any skipped item explicitly.
