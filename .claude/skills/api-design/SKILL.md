---
name: api-design
description: Design or review HTTP/library APIs. Use when defining endpoints, schemas, function signatures, or versioning.
---

- Resources as nouns, correct verbs and status codes, consistent naming and casing.
- Idempotency for PUT/DELETE and retried POSTs (idempotency keys).
- Pagination, filtering, and sorting from day one; stable cursors for large sets.
- Uniform error shape: code, message, details, request id.
- Validate input at the boundary; document with OpenAPI.
- Plan versioning and deprecation; never break existing clients silently.
