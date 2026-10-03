---
title: "Create a regression test"
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

# Create a regression test

## When to use it

After fixing a bug.

## Copy-ready prompt

```text
Using the reproduced bug, first write the smallest regression scenario.

The test must:
- fail before the fix;
- pass after the fix;
- reflect the root cause or observable behavior;
- avoid unnecessary implementation details.

Only then propose the smallest fix.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
