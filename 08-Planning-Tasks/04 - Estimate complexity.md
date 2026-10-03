---
title: "Estimate complexity"
format: prompt
archetype: instruction
domain: planning
tags:
  - planning
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
expected_output: "actionable plan/tasks"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Estimate complexity

## When to use it

For planning without adding financial costs to Stories.

## Copy-ready prompt

```text
Estimate only the complexity and relative effort of these tasks.

Use:
- small;
- medium;
- large;
- complex.

Justify based on:
- unknowns;
- code surface;
- dependencies;
- migration;
- security;
- tests;
- integrations;
- frontend;
- risk.

Do not include any price or financial cost.

Output: actionable plan/tasks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Actionable plan/tasks.
