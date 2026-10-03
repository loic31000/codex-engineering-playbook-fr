---
title: "Implement a Story"
format: prompt
archetype: workflow
domain: implementation
tags:
  - implementation
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
expected_output: "controlled, tested implementation within scope"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Implement a Story

## When to use it

After the Story is READY.

## Copy-ready prompt

```text
Implement only the provided Story.

Context to use:
- the Story and its acceptance criteria;
- the plan if one exists;
- only the repository conventions and files that are actually relevant.

Before modifying code, identify only ambiguities that would materially change behavior, security, data, or a public contract. If there are none, continue without asking for confirmation.

During implementation:
- stay within scope;
- respect the existing architecture and conventions;
- prefer the smallest sufficient change;
- do not add a dependency without flagging it;
- do not weaken security or test coverage.

Validation:
- run directly affected tests and mandatory project checks;
- map each acceptance criterion to the code and/or test that verifies it.

Final output:
- change summary;
- acceptance criteria covered;
- main files modified;
- tests run and results;
- remaining assumptions or decisions.

If an essential business or security decision is missing, stop only the affected part and explain what must be decided.
```

## Expected output

A controlled, tested implementation within scope.
