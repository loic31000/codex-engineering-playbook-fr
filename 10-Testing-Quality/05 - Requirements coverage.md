---
title: "Verify requirements coverage"
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

# Verify requirements coverage

## When to use it

Before declaring a Story complete.

## Copy-ready prompt

```text
Build a matrix:

Acceptance Criterion
→ verification method
→ test(s)
→ status

Identify:
- acceptance criteria without a test/verification;
- tests without a clear requirement;
- uncovered edge cases;
- uncovered security requirements;
- excessive dependence on manual testing.

Do not confuse code coverage with requirements coverage.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
