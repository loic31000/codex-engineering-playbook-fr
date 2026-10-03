---
title: "Prepare a technical spike"
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

# Prepare a technical spike

## When to use it

When an unknown blocks a decision.

## Copy-ready prompt

```text
Turn this unknown into a bounded technical spike.

Define:
- exact question;
- assumptions;
- what must be experimented with;
- what must not be built;
- bounded duration/effort;
- decision criteria;
- expected final artifact.

The spike must reduce uncertainty, not become hidden implementation work.

Output: actionable plan/tasks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Actionable plan/tasks.
