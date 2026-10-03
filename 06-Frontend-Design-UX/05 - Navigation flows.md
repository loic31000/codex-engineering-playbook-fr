---
title: "Design navigation and flows"
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

# Design navigation and flows

## When to use it

When information architecture or user flows are confusing.

## Copy-ready prompt

```text
Analyze users' main tasks and propose a navigation architecture.

Define:
- primary navigation;
- secondary navigation;
- breadcrumb when useful;
- depth;
- routes;
- entry points;
- exits;
- back navigation;
- persistent states;
- tenant/project context;
- mobile navigation.

For each critical flow, provide:
- trigger;
- minimum steps;
- user decisions;
- possible errors;
- success state.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
