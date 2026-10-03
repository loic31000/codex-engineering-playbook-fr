---
title: "Incremental implementation"
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

# Incremental implementation

## When to use it

To reduce risk on a large change.

## Copy-ready prompt

```text
Implement this change in safe increments.

Before each increment:
- precise objective;
- behavior to preserve;
- planned test.

After each increment:
- run relevant tests;
- summarize the result;
- verify that the next increment is still valid.

Do not combine several independent changes in the same increment.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
