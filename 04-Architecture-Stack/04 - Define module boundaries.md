---
title: "Define modules and boundaries"
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

# Define modules and boundaries

## When to use it

When structuring a monolith or a set of services.

## Copy-ready prompt

```text
Propose module boundaries from the provided domain information.

Use:
- use cases;
- business rules and invariants;
- data ownership;
- existing dependencies;
- already confirmed constraints.

For each proposed module:
- responsibility;
- owned data;
- exposed contracts;
- allowed and forbidden dependencies;
- possible events;
- invariants;
- reasons for the boundary.

Then list:
- problematic couplings;
- still-uncertain decisions;
- credible alternatives and their trade-offs.

Prefer business boundaries over technical-layer decomposition.
Do not create a bounded context merely to obtain a symmetrical architecture.
Do not invent business rules absent from the context.
```

## Expected output

A structured architecture analysis or decision.
