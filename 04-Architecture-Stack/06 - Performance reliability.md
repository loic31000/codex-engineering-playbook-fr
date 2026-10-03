---
title: "Performance and reliability architecture"
format: prompt
archetype: instruction
domain: architecture
tags:
  - architecture
status: draft
version: "0.2.0"
source_branch: main
source_version: "0.2.0"
language: en
tools:
  - codex
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
last_revision: 2026-10-03
required_inputs:
  - provided-context
expected_output: "structured architecture analysis or decision"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Performance and reliability architecture

## When to use it

When a feature has load, latency, or availability concerns.

## Copy-ready prompt

```text
Analyze this architecture from a performance and reliability perspective.

Evaluate:
- critical path;
- latency;
- throughput;
- contention;
- cache;
- I/O;
- timeouts;
- retries;
- idempotency;
- backpressure;
- circuit breakers;
- queues;
- degradation;
- recovery;
- observability.

Do not optimize prematurely.
Separate:
- demonstrated risks;
- plausible risks;
- optimizations that should be measured before deciding.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
