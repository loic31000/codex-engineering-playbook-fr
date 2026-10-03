---
title: "Review from a visual reference"
format: prompt
archetype: checklist
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
  - screenshot-or-reference
  - current-implementation
expected_output: "prioritized visual gaps with evidence and corrections"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Review from a visual reference

## When to use it

When a screenshot, mockup, or visual reference must be compared with the implemented interface.

## Copy-ready prompt

```text
Compare the provided visual reference with the current interface.

Evaluate:
- structure and hierarchy;
- spacing and alignments;
- typography;
- colors and contrast;
- components;
- density;
- visible interactive states;
- responsive behavior when several views are available.

For each difference:
- observable evidence;
- impact on consistency or use;
- priority;
- minimal correction.

Distinguish intentional differences, confirmed gaps, and elements that cannot be verified.
Do not blindly copy a reference when it conflicts with product or accessibility constraints.
```

## Expected output

A prioritized and actionable visual review.
