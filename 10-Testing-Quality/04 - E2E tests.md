---
title: "Design critical E2E tests"
format: prompt
archetype: workflow
domain: testing-quality
tags:
  - testing
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
expected_output: "risk-aligned test strategy or test suite"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Design critical E2E tests

## When to use it

For essential user journeys.

## Copy-ready prompt

```text
Using the acceptance criteria, select the journeys that deserve an E2E test.

For each scenario:
- preconditions;
- user steps;
- visible result;
- assertions;
- data;
- cleanup;
- errors;
- browser/device when relevant.

Avoid duplicating the entire unit-test suite in E2E tests.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
