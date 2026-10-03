---
title: "Spec/code/tests convergence"
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

# Spec/code/tests convergence

## When to use it

After implementation, before a PR.

## Copy-ready prompt

```text
Verify convergence between:
- Story/spec;
- plan;
- code;
- tests;
- documentation.

Build a matrix:
- requirement;
- implementation;
- test;
- documentation;
- status.

Identify:
- forgotten requirement;
- code outside scope;
- missing test;
- outdated documentation;
- undocumented technical decision.

Do not modify the spec merely to justify the code.

Output: a prioritized and actionable review.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritized and actionable review.
