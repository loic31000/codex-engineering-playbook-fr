---
title: "Define MVP scope"
format: prompt
archetype: instruction
domain: product
tags:
  - mvp
  - scope
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
expected_output: "defensible and limited MVP scope"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Define MVP scope

## When to use it

When you need to prevent the MVP from continuously growing.

## Copy-ready prompt

```text
Help me define the MVP scope.

Classify capabilities as:
- essential to the core problem;
- useful but deferrable;
- explicitly out of MVP;
- unknown / decision required.

For each essential capability:
- affected user;
- value delivered;
- dependencies;
- risk;
- criterion for considering it sufficiently complete for the MVP.

Do not propose additional features unless you place them under "possible future."

Output: a defensible and limited MVP scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A defensible and limited MVP scope.

## Control points

- [ ] Out-of-scope section present
- [ ] No feature creep
