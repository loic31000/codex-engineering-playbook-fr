---
title: "Define visual direction"
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

# Define visual direction

## When to use it

When you want a coherent visual language before coding screens.

## Copy-ready prompt

```text
Define a visual direction suited to the provided product.

Prioritize:
- audience and usage context;
- frequency of use;
- brand positioning;
- existing design;
- provided visual references.

Produce:
- design intent in 2–3 sentences;
- 4 to 6 guiding adjectives;
- hierarchy and density;
- typography;
- palette and color roles;
- layout principles;
- components and surfaces;
- iconography / imagery;
- motion;
- elements to avoid.

Adapt the style to the domain: a frequently used operational tool should prioritize efficiency, scannability, and repetition; an editorial or playful experience can be more expressive.

If visual references are provided, extract their useful principles without copying them literally.

Flag visual decisions that require human validation.
```

## Expected output

A directly actionable frontend/design recommendation.
