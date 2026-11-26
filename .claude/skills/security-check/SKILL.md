---
name: security-check
description: Audit code or config for security problems. Use before release, on auth/input handling code, or when asked about vulnerabilities.
---

Check, in order: hardcoded secrets and keys; injection (SQL, shell, XSS, path traversal); authn/authz gaps and IDOR; unsafe deserialization; SSRF and open redirects; dependency CVEs; overly broad CORS/permissions; sensitive data in logs.

Report each finding with file:line, severity, exploit scenario, and a concrete fix. Do not report style issues as security issues. Never print discovered secret values; reference their location.
Only assist with defensive review of code the user owns or is authorized to test.
