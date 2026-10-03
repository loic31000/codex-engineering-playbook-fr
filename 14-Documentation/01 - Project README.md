---
title: "Write a project README"
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

# Write a project README

## When to use it

For fast onboarding.

## Copy-ready prompt

```text
Write a project README useful to a developer.

Include:
- objective;
- quick architecture overview;
- prerequisites;
- installation;
- configuration without secrets;
- commands;
- tests;
- structure;
- workflow;
- additional documentation;
- minimal troubleshooting.

Avoid duplicating all technical documentation.

Output: concise, current, usage-oriented documentation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Concise, current, usage-oriented documentation.
