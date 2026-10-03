---
title: "Document the data model"
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

# Document the data model

## When to use it

To understand ownership and constraints.

## Copy-ready prompt

```text
Write engineering-oriented documentation for the data model.

Include:
- entities;
- ownership;
- relationships;
- invariants;
- sensitivity;
- retention;
- migrations;
- tenant isolation;
- important indexes/constraints.

Avoid simply copying the SQL schema.

Output: concise, current, usage-oriented documentation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Concise, current, usage-oriented documentation.
