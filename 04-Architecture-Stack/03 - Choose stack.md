---
title: "Choose a stack"
format: prompt
archetype: instruction
domain: architecture
tags:
  - architecture
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
expected_output: "structured architecture analysis or decision"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Choose a stack

## When to use it

When several technologies are viable.

## Copy-ready prompt

```text
Compare stack options only against the project's needs.

Criteria:
- product fit;
- available expertise;
- ecosystem;
- security;
- testability;
- maturity;
- maintainability;
- required performance;
- deployment;
- longevity;
- lock-in.

Distinguish:
- constraints;
- preferences;
- recommended choices;
- still-open decisions.

Avoid choices motivated only by trends.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
