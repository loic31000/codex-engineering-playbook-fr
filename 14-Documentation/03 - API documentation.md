---
title: "Document an API"
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

# Document an API

## When to use it

After design/implementation.

## Copy-ready prompt

```text
Write documentation for this API.

For each endpoint/operation:
- objective;
- auth;
- input;
- output;
- errors;
- short examples;
- pagination/filtering;
- idempotency;
- rate limiting;
- versioning.

Add breaking changes and compatibility policies.

Output: concise, current, usage-oriented documentation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Concise, current, usage-oriented documentation.
