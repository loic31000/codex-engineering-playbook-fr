---
title: "Break a plan into tasks"
format: prompt
archetype: workflow
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

# Break a plan into tasks

## When to use it

After the plan has been validated.

## Copy-ready prompt

```text
Break this plan into small, ordered tasks.

Each task must:
- have one objective;
- produce a verifiable result;
- state dependencies;
- identify likely files/components;
- include tests;
- remain small enough for a clear review.

Avoid vague tasks such as "do the frontend."

Output: actionable plan/tasks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Actionable plan/tasks.
