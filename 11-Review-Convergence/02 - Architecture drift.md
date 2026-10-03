---
title: "Detect architecture drift"
format: prompt
archetype: checklist
domain: review-convergence
tags:
  - review
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
expected_output: "prioritized and actionable review"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Detect architecture drift

## When to use it

To verify that a feature does not erode architectural boundaries.

## Copy-ready prompt

```text
Compare this change with the documented architecture.

Look for:
- reversed dependency;
- forbidden direct access;
- business logic in the wrong layer;
- duplicated concepts;
- circular dependency;
- undocumented new abstraction;
- persistence crossing a boundary;
- bypass of an internal API.

Classify:
- blocking drift;
- acceptable debt;
- false positive.

Output: a prioritized and actionable review.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritized and actionable review.
