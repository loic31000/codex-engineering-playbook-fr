---
title: "Formalize the product vision"
format: prompt
archetype: instruction
domain: product
tags:
  - product
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
expected_output: "product vision usable for the next specification steps"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Formalize the product vision

## When to use it

When the idea exists but has not yet been formulated clearly.

## Copy-ready prompt

```text
Using the available information, write a concise product vision.

Structure:
- problem;
- target users;
- context;
- expected outcome;
- value proposition;
- success indicators;
- non-goals;
- product assumptions;
- open questions.

Do not invent metrics when they are unknown.
Turn vague statements into questions when necessary.

Output: a product vision usable for the next specification steps.
```

## Expected output

A product vision usable for the next specification steps.

## Control points

- [ ] Problem distinct from solution
- [ ] Explicit non-goals
