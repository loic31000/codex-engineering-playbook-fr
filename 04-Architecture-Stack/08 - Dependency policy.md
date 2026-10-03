---
title: "Dependency policy"
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

# Dependency policy

## When to use it

To avoid uncontrolled library proliferation.

## Copy-ready prompt

```text
Define a simple policy for new dependencies.

Include:
- when an external dependency is justified;
- evaluation criteria;
- security/supply chain;
- maintenance;
- size/runtime cost;
- license;
- lockfile;
- native alternatives;
- review procedure;
- rule for removing unused dependencies.

The policy must remain short and actionable.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
