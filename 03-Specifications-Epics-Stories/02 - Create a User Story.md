---
title: "Create a User Story"
format: prompt
archetype: template
domain: specifications
tags:
  - spec
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
expected_output: "testable Story ready for clarification"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Create a User Story

## When to use it

When a need must become a unit of work.

## Copy-ready prompt

```text
Transform the provided need into a focused and testable User Story.

Output:
- title;
- affected user or actor;
- need or objective;
- desired value;
- scope;
- out of scope;
- observable acceptance criteria;
- important edge cases;
- known dependencies;
- security / data / UI / API impacts;
- verification method.

Do not add any financial cost.
Do not add implementation details that are not already constrained.

If the need contains several independent outcomes, do not create one giant Story: propose a split into vertical Stories and briefly explain the boundary.

Mark any unknown information as "to clarify" instead of inventing it.
```

## Expected output

A testable Story ready for clarification.
