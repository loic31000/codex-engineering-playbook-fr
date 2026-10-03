---
title: "Optimize after measurement"
format: prompt
archetype: workflow
domain: implementation
tags:
  - implementation
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
expected_output: "controlled, tested implementation within scope"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Optimize after measurement

## When to use it

When a bottleneck has been observed.

## Copy-ready prompt

```text
Using the provided measurements/profiling, propose and then implement the smallest optimization that addresses the primary cause.

Before:
- summarize the metric;
- identify the likely cause;
- define the expected result.

After:
- reproduce the measurement;
- compare before/after;
- check for regressions;
- avoid optimizations without measured impact.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
