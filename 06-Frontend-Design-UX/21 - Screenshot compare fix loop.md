---
title: "Screenshot → compare → fix loop"
format: prompt
archetype: workflow
domain: frontend-design-ux
tags:
  - frontend
  - design
  - visual-qa
status: draft
version: "0.1.0"
source_branch: main
source_version: "0.1.0"
language: en
tools:
  - codex
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
last_revision: 2026-10-03
required_inputs:
  - visual-reference
  - implementation-screenshot
expected_output: "incremental visual correction loop with verification"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Screenshot → compare → fix loop

## When to use it

When a frontend implementation must progressively converge toward a visual reference.

## Copy-ready prompt

```text
Make the interface converge toward the visual reference through small, verifiable corrections.

At each iteration:
1. compare the current screenshot with the reference;
2. identify the 1 to 3 most important differences;
3. propose or apply the smallest correction;
4. request or produce a new screenshot if the tool allows it;
5. compare again before continuing.

Prioritize structure, hierarchy, spacing, typography, and responsive behavior before decorative details.

Do not change product behavior just to obtain visual similarity.
Respect accessibility and the existing design system.

Final output:
- corrected gaps;
- remaining gaps;
- intentional differences;
- verification performed.
```

## Expected output

Incremental visual convergence rather than a global rewrite.
