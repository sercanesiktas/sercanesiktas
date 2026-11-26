---
name: sql-helper
description: Write, debug, and optimize SQL and schema migrations. Use for queries, indexes, joins, and database design.
---

- Ask or detect the dialect (Postgres, MySQL, SQLite) first.
- Use explicit JOINs, CTEs for readability, parameterized queries only (never string-concat user input).
- Read `EXPLAIN` output before adding indexes; index for actual filters and joins.
- Migrations: reversible, small, safe on large tables (avoid long locks), data backfill separate from schema change.
- Test on a copy before suggesting destructive statements; warn before any DELETE/DROP/UPDATE without WHERE.
