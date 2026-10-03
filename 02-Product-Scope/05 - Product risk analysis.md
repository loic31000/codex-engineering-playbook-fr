---
title: "Analyze product risks"
format: prompt
archetype: instruction
domain: product
tags:
  - risk
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
expected_output: "prioritizable product risk register"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Analyze product risks

## When to use it

Before an MVP or a large feature.

## Copy-ready prompt

```text
Analyze the product risks of this initiative.

For each risk:
- description;
- category;
- qualitative probability;
- impact;
- warning signal;
- mitigation;
- associated decision.

Look especially for:
- wrong problem;
- wrong user;
- overly broad scope;
- external dependency;
- undefined critical behavior;
- adoption;
- legal constraints;
- UX debt.

Do not mix technical risks with established facts.

Output: a prioritizable product risk register.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritizable product risk register.

## Control points

- [ ] Risk ≠ certainty
- [ ] Concrete mitigations
