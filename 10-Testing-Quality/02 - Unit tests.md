---
title: "Write relevant unit tests"
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

# Write relevant unit tests

## When to use it

During or after implementation of a business unit.

## Copy-ready prompt

```text
Analyze this code and write only unit tests that provide real value.

Cover:
- business rules;
- boundaries;
- errors;
- meaningful branches;
- invariants.

Avoid:
- tests that merely repeat the implementation;
- excessive mocks;
- framework tests;
- fragile assertions.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
