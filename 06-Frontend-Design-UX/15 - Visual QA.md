---
title: "Frontend visual QA"
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

# Frontend visual QA

## When to use it

After implementing a screen or before a PR.

## Copy-ready prompt

```text
Act as a product designer and frontend reviewer.

Compare the implementation with the available visual and UX requirements.

Verify:
- hierarchy;
- alignments;
- spacing;
- typography;
- colors;
- radius/borders/shadows;
- iconography;
- dimensions;
- responsive behavior;
- overflow;
- states;
- focus;
- hover;
- disabled;
- errors;
- empty/loading;
- consistency with the design system.

Classify:
- functional divergence;
- major visual divergence;
- minor polish.

Do not propose a redesign if the implementation already respects the specification.

Output: a directly actionable frontend/design recommendation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A directly actionable frontend/design recommendation.
