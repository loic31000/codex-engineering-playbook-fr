---
title: "Implement a DB migration"
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

# Implement a DB migration

## When to use it

After the migration plan has been validated.

## Copy-ready prompt

```text
Implement this migration safely.

Follow the validated plan.

Verify:
- forward compatibility;
- backfill;
- constraints;
- indexes;
- potential locks;
- code/schema deployment order;
- rollback or forward fix;
- existing data;
- tests.

Do not perform destructive deletion prematurely.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
