---
title: "WCAG 2.2 accessibility review"
format: prompt
archetype: checklist
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
standard:
  name: "WCAG 2.2"
  level: "AA"
  last_verified: 2026-10-03
---

# WCAG 2.2 accessibility review

## When to use it

For a UI before merge or during design.

## Copy-ready prompt

```text
Audit the provided interface against WCAG 2.2, level AA by default.

Strictly separate:
1. WCAG compliance failures;
2. points that cannot be confirmed with the available evidence;
3. non-blocking accessibility best practices.

Examine in particular:
semantics, headings, landmarks, labels, keyboard, focus, focus order, contrast, zoom/reflow, touch targets, text alternatives, status messages, dialogs, forms, drag-and-drop, accessible authentication, and animations.

For each potential failure, provide:
- WCAG 2.2 success criterion and level when you can identify it confidently;
- observed evidence;
- user impact;
- reproduction method;
- minimal correction;
- re-test method.

Do not declare an interface "WCAG compliant" when some criteria require verification you cannot perform.

Classify results as: blocker / important / improvement.
```

## Expected output

A directly actionable frontend/design recommendation.
