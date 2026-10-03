---
title: "Create a developer onboarding guide"
format: prompt
archetype: template
domain: documentation
tags:
  - documentation
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
expected_output: "concise, current, usage-oriented documentation"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Create a developer onboarding guide

## When to use it

For new developers.

## Copy-ready prompt

```text
Create a developer onboarding journey.

Order:
- understand the product;
- run locally;
- tests;
- architecture;
- conventions;
- first small task;
- CI;
- deployment;
- security;
- where to ask questions.

Aim for a fast first contribution without hiding important rules.

Output: concise, current, usage-oriented documentation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Concise, current, usage-oriented documentation.
