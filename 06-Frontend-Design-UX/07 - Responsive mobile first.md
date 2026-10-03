---
title: "Responsive mobile-first design"
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

# Responsive mobile-first design

## When to use it

When a screen must work from mobile to desktop.

## Copy-ready prompt

```text
Review this screen mobile-first.

For each logical breakpoint, assess:
- content priority;
- order;
- width;
- grid;
- navigation;
- tables/lists;
- actions;
- overlays;
- forms;
- typography;
- touch targets;
- overflow.

Do not merely "stack everything."
Explain what actually changes in composition between small and large screens.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
