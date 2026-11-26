---
name: write-tests
description: Write or improve automated tests. Use when asked for tests, coverage, or when changing behavior that lacks tests.
---

- Match the project's existing framework, layout, and naming. Read two existing tests first.
- Test behavior and public contracts, not implementation details.
- Cover: happy path, edge cases (empty, null, boundary), error paths.
- One reason to fail per test; descriptive names; no shared mutable state.
- Mock only at system boundaries (network, clock, disk).
- Run the suite and show the result. A test you did not run is not done.
