---
title: "Synchronize documentation and code"
format: prompt
archetype: workflow
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

# Synchronize documentation and code

## When to use it

After a large PR.

## Copy-ready prompt

```text
Compare durable documentation with the current code.

Identify:
- outdated documentation;
- undocumented behaviors;
- architecture drift;
- broken commands;
- missing configuration;
- changed endpoints;
- unrecorded decisions.

Propose only the necessary updates.

Output: concise, current, usage-oriented documentation.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Concise, current, usage-oriented documentation.
