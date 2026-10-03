---
title: "Frontend architecture"
format: prompt
archetype: workflow
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

# Frontend architecture

## When to use it

At the beginning of a web app or during a structural redesign.

## Copy-ready prompt

```text
Act as a senior frontend architect.

Based on the product and its constraints, propose the frontend architecture.

Cover:
- routing;
- layout;
- server/client separation when applicable;
- data fetching;
- local/global state;
- forms;
- error handling;
- UI-side auth;
- shared components;
- design system;
- testing;
- performance;
- accessibility;
- frontend observability.

Favor simplicity.
Do not introduce global state or an abstraction without a clear need.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
