---
title: "Implement an API change"
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

# Implement an API change

## When to use it

When modifying an existing contract.

## Copy-ready prompt

```text
Implement this API change while protecting existing consumers.

Verify:
- current contract;
- breaking change;
- versioning;
- validation;
- errors;
- auth;
- observability;
- documentation;
- contract tests;
- consumer migration.

If the change is breaking, do not hide it behind a silent implementation.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
