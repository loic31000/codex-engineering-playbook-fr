---
title: "Design themes and dark mode"
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

# Design themes and dark mode

## When to use it

When the product requires multiple themes.

## Copy-ready prompt

```text
Design a robust theming system.

Define semantic tokens rather than component-coded colors.

Cover:
- background/surface;
- text;
- borders;
- brand;
- interactive;
- success/warning/error;
- focus;
- overlays;
- charts;
- syntax when applicable.

Verify:
- contrast;
- images/logos;
- shadows;
- elevation;
- system preference;
- theme switching;
- flash on load.

Do not merely invert colors.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
