---
title: "Create an ExecPlan"
format: prompt
archetype: template
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

# Create an ExecPlan

## When to use it

For a complex Story, migration, or significant refactor.

## Copy-ready prompt

```text
Create a detailed execution plan without writing code.

Include:
- objective;
- context;
- preconditions;
- affected files/components;
- implementation sequence;
- migrations;
- APIs;
- security;
- tests;
- rollout;
- rollback;
- risks;
- verification points.

The plan must be executable by another developer without needing this conversation.

Output: actionable plan/tasks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Actionable plan/tasks.
