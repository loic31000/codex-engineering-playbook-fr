---
title: "Frontend component tests"
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

# Frontend component tests

## When to use it

For UI components with logic and states.

## Copy-ready prompt

```text
Define useful tests for these components.

Prioritize:
- user behavior;
- accessibility;
- states;
- errors;
- interactions;
- callbacks;
- responsive logic when testable.

Avoid testing:
- trivial CSS details;
- exact DOM structure without a reason;
- framework internals.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
