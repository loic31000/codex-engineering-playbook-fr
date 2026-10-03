---
title: "Personas and Jobs To Be Done"
format: prompt
archetype: instruction
domain: product
tags:
  - product
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
expected_output: "functional profiles useful for Stories and UX"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Personas and Jobs To Be Done

## When to use it

When users are still described too vaguely.

## Copy-ready prompt

```text
Using the real context provided, formalize the main user profiles.

For each:
- role/context;
- primary goal;
- Job To Be Done;
- trigger;
- frustrations;
- constraints;
- expertise level;
- important decisions they must make in the product.

Avoid invented marketing personas.
Do not add demographic data without product value.

Output: functional profiles useful for Stories and UX.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Functional profiles useful for Stories and UX.

## Control points

- [ ] No fictional details
- [ ] JTBD focused on outcomes
