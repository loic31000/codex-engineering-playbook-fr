---
title: "Create a test strategy"
format: prompt
archetype: checklist
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

# Create a test strategy

## When to use it

At the project or large-feature level.

## Copy-ready prompt

```text
Define a test strategy proportional to risk.

Distribute coverage across:
- unit;
- integration;
- contract;
- E2E;
- accessibility;
- security;
- performance when necessary.

For each type:
- objective;
- what it covers;
- what it should not cover;
- speed;
- environment;
- data;
- CI trigger.

Prioritize requirements and risk coverage over an arbitrary percentage.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
