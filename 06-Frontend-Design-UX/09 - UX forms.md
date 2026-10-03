---
title: "Design a robust form"
format: prompt
archetype: instruction
domain: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
expected_output: "directly actionable frontend/design recommendation"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Design a robust form

## When to use it

For login, checkout, onboarding, settings, and similar flows.

## Copy-ready prompt

```text
Design this form to minimize errors and friction.

Define:
- field order;
- grouping;
- labels;
- help text;
- required fields;
- validation;
- server/client validation;
- inline/global errors;
- data preservation;
- submit behavior;
- double-submit handling;
- loading;
- success;
- keyboard/mobile behavior;
- autofill;
- accessibility.

Do not use a placeholder as the only label.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
