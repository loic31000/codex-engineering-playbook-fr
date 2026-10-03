---
title: "Evaluate prompt quality"
format: prompt
archetype: checklist
domain: meta-prompting
tags:
  - prompting
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
expected_output: "more robust prompt or workflow"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Evaluate prompt quality

## When to use it

When stabilizing the library.

## Copy-ready prompt

```text
Evaluate this prompt across 10 dimensions:

- clear objective;
- sufficient context;
- scope;
- constraints;
- expected output;
- testability;
- absence of ambiguity;
- absence of over-guidance;
- escalation conditions;
- reusability.

For each dimension:
- problem;
- impact;
- correction.

Then propose a revised version.
```

## Expected output

A more robust prompt or workflow.
