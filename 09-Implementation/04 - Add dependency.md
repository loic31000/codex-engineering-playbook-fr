---
title: "Evaluate and add a dependency"
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

# Evaluate and add a dependency

## When to use it

Before npm install/pip install/etc.

## Copy-ready prompt

```text
Before adding this dependency, evaluate whether it is genuinely necessary.

Compare:
- native solution;
- small local implementation;
- proposed dependency;
- alternatives.

Evaluate:
- maintenance;
- maturity;
- security;
- size;
- transitive dependencies;
- license;
- API;
- lock-in.

If the dependency is selected, explain:
- why;
- version;
- usage area;
- test plan.

Output: a controlled, tested implementation within scope.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A controlled, tested implementation within scope.
