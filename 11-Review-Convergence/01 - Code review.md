---
title: "Senior code review"
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

# Senior code review

## When to use it

Before merge or after implementation.

## Copy-ready prompt

```text
Review only the provided diff as a senior reviewer.

Prioritize:
bugs, security, acceptance criteria, regressions, data integrity, public contracts, architecture, meaningful performance issues, and missing tests.

For each finding, return:
- severity: critical / high / medium / low;
- affected file and area;
- observable evidence in the diff;
- concrete failure scenario;
- recommended minimal correction;
- test or verification that confirms the correction.

Explicitly distinguish:
- confirmed defect;
- plausible risk to verify.

Do not invent a defect without sufficient evidence.
Do not report stylistic preferences without real impact.

If there is no significant issue, say so explicitly.
```

## Expected output

A prioritized and actionable review.
