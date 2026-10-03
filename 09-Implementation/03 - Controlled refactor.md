---
title: "Controlled refactor"
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

# Controlled refactor

## When to use it

When you want to improve structure without changing behavior.

## Copy-ready prompt

```text
Refactor this code without changing observable behavior.

Before:
- describe the behavior to preserve;
- identify protective tests;
- identify risks.

During:
- make small steps;
- do not mix feature work and refactoring;
- remove unnecessary abstractions;
- reduce duplication/coupling when readability is preserved.

After:
- compare behavior/tests;
- list structural changes;
- flag any intentional difference.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
