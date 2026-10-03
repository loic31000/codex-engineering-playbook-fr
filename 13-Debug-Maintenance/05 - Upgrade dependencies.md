---
title: "Plan dependency upgrades"
format: prompt
archetype: workflow
domain: debug-maintenance
tags:
  - debug
  - maintenance
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
expected_output: "evidence-based diagnosis or maintenance plan"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Plan dependency upgrades

## When to use it

Before a major upgrade.

## Copy-ready prompt

```text
Prepare the upgrade of these dependencies.

For each:
- current/target version;
- breaking changes;
- deprecations;
- security;
- affected code;
- migration;
- tests;
- order;
- rollback.

Avoid grouping major upgrades without a clear need.

Output: an evidence-based diagnosis or maintenance plan.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An evidence-based diagnosis or maintenance plan.
