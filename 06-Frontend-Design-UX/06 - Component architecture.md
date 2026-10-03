---
title: "Component architecture"
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

# Component architecture

## When to use it

Before splitting a screen into React/Vue/etc. components.

## Copy-ready prompt

```text
Propose a component architecture for this screen/feature.

For each component:
- responsibility;
- input data;
- emitted events;
- local state;
- dependencies;
- actual reusability;
- required test.

Distinguish:
- design-system primitives;
- domain components;
- page components;
- business logic.

Avoid overly generic components and boolean props that explode into combinations.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
