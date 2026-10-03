---
title: "Design loading, empty, error, and success states"
format: prompt
archetype: instruction
domain: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
expected_output: "directly actionable frontend/design recommendation"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Design loading, empty, error, and success states

## When to use it

When a screen has only been defined for the happy path.

## Copy-ready prompt

```text
For this interface, specify all important states:

- initial loading;
- partial loading;
- skeleton when relevant;
- first-use empty state;
- empty state after filtering;
- network error;
- permission error;
- validation error;
- stale data;
- retry;
- success;
- long-running processing;
- offline when relevant.

For each:
- message;
- possible action;
- tone;
- component;
- accessibility;
- preservation of user context.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
