---
title: "Plan a database migration"
format: prompt
archetype: workflow
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

# Plan a database migration

## When to use it

Before a risky schema change.

## Copy-ready prompt

```text
Prepare a safe data migration plan.

Include:
- current state;
- target state;
- schema migration;
- data migration;
- compatibility during deployment;
- step order;
- backfill;
- constraints/indexes;
- rollback or forward-only strategy;
- availability impact;
- checks before/after;
- tests.

Avoid destructive one-step migrations when the system is in production.

Output: explicit and verifiable data/API design.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An explicit and verifiable data/API design.
