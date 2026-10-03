---
title: "Analyze dependencies and ordering"
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

# Analyze dependencies and ordering

## When to use it

When several tasks may block one another.

## Copy-ready prompt

```text
Build the dependency graph for these tasks.

For each task:
- depends on;
- blocks;
- can run in parallel;
- risk;
- proof of completion.

Propose an order that maximizes:
- fast feedback;
- risk reduction;
- parallel work;
- availability of foundations.

Output: actionable plan/tasks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Actionable plan/tasks.
