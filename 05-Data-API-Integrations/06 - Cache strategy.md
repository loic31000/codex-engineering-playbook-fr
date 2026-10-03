---
title: "Design a cache strategy"
format: prompt
archetype: instruction
domain: data-api
tags:
  - data
  - api
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
expected_output: "explicit and verifiable data/API design"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Design a cache strategy

## When to use it

When performance or cost justifies caching.

## Copy-ready prompt

```text
Before proposing a cache, verify that it addresses a measured or plausible problem.

Define:
- cached data;
- key;
- TTL;
- invalidation;
- consistency;
- stampede;
- sensitive data;
- multi-tenancy;
- fallback;
- observability;
- stale-data risk.

Also explain when NOT to use a cache.

Output: explicit and verifiable data/API design.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An explicit and verifiable data/API design.
