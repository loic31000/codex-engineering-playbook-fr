---
title: "Design an API"
format: prompt
archetype: instruction
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

# Design an API

## When to use it

Before implementing a new or modified API.

## Copy-ready prompt

```text
Design the API contract for this feature.

Specify:
- resources/operations;
- inputs;
- outputs;
- validation;
- auth/permissions;
- error codes;
- pagination/filtering when applicable;
- idempotency;
- versioning;
- rate limiting when necessary;
- errors;
- observability.

Separate the public contract from internal details.
Flag any breaking change.

Output: explicit and verifiable data/API design.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An explicit and verifiable data/API design.
