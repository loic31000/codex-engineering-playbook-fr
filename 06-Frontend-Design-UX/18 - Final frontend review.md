---
title: "Final frontend review"
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

# Final frontend review

## When to use it

Before merging a frontend feature.

## Copy-ready prompt

```text
Perform a complete frontend review of this diff.

Evaluate:
- Story compliance;
- component architecture;
- state management;
- data fetching;
- errors;
- responsive behavior;
- accessibility;
- design system;
- performance;
- frontend security;
- tests;
- duplication;
- dead code;
- UX consistency.

Separate:
- blockers;
- recommendations;
- optional polish.

Do not request a refactor without concrete impact.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
