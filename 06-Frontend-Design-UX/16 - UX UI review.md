---
title: "Critical UX/UI review"
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
---

# Critical UX/UI review

## When to use it

When a screen exists but feels difficult or inconsistent.

## Copy-ready prompt

```text
Perform a structured UX/UI critique of this interface.

Evaluate:
- clarity of the objective;
- hierarchy;
- cognitive load;
- discoverability;
- affordances;
- feedback;
- consistency;
- errors;
- density;
- navigation;
- mobile;
- accessibility;
- trust;
- friction.

For each issue:
- observable evidence;
- user impact;
- priority;
- minimal correction;
- a more ambitious option when useful.

Avoid unjustified personal taste.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
