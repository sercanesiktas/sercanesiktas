---
name: perf-tune
description: Find and fix performance problems. Use for slow endpoints, high memory/CPU, slow builds, or slow queries.
---

1. Measure first: profiler, timings, query plans. No optimizing by guesswork.
2. Identify the single biggest bottleneck; fix that.
3. Typical wins: N+1 queries, missing indexes, repeated work (cache), needless allocation, blocking I/O, oversized payloads.
4. Re-measure and report before/after numbers.
5. Stop when the target is met; avoid complexity for marginal gains.
