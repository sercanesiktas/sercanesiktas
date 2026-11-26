---
name: ci-debug
description: Diagnose failing CI/CD pipelines, GitHub Actions, builds, and deploys.
---

1. Fetch the failing job's logs and find the first real error, not the last line.
2. Decide: code bug, flaky test, env/config drift, dependency change, or infra issue.
3. Reproduce locally with the same versions and commands where possible.
4. Fix the cause. Never skip, disable, or quarantine a test just to get green.
5. Pin versions, cache correctly, and keep workflows minimal and least-privilege.
