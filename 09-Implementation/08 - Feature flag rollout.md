---
title: "Implement with a feature flag"
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

# Implement with a feature flag

## When to use it

To reduce rollout risk.

## Copy-ready prompt

```text
Plan and implement this feature behind a feature flag.

Define:
- flag;
- default value;
- population;
- off behavior;
- on behavior;
- possible data migration;
- analytics/observability;
- rollback;
- flag-removal date/condition.

Avoid permanent flags without an owner.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
