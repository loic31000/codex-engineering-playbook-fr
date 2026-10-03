---
title: "Accessibility test plan"
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

# Accessibility test plan

## When to use it

For a UI feature.

## Copy-ready prompt

```text
Define the accessibility tests for this interface.

Include:
- automated checks;
- keyboard navigation;
- focus;
- targeted screen-reader testing;
- contrast;
- zoom/reflow;
- reduced motion;
- forms;
- errors;
- dialogs;
- mobile/touch.

Distinguish what can be automated from what requires manual verification.

Output: a risk-aligned test strategy or test suite.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A risk-aligned test strategy or test suite.
