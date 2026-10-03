---
title: "Design the data model"
format: prompt
archetype: template
domain: data-api
tags:
  - data
  - api
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
expected_output: "explicit and verifiable data/API design"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Design the data model

## When to use it

When entities and relationships need to be formalized.

## Copy-ready prompt

```text
Based on confirmed business rules, propose a conceptual data model.

For each entity:
- responsibility;
- identifier;
- essential attributes;
- relationships;
- cardinalities;
- invariants;
- ownership;
- lifecycle;
- uniqueness constraints;
- data sensitivity.

Do not choose unnecessary storage details yet.
Flag business ambiguities.

Output: explicit and verifiable data/API design.
```

## Expected output

An explicit and verifiable data/API design.
