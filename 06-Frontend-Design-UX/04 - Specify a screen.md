---
title: "Specify a screen"
format: prompt
archetype: template
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

# Specify a screen

## When to use it

Before implementing a frontend screen.

## Copy-ready prompt

```text
Specify this screen as a product designer and senior frontend developer.

Describe:
- user objective;
- primary information;
- visual hierarchy;
- sections;
- components;
- primary/secondary actions;
- loading/empty/error/success states;
- permissions;
- validation;
- responsive behavior;
- keyboard;
- focus;
- accessibility;
- optional analytics;
- edge cases.

Finish with a top-to-bottom textual screen structure.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
