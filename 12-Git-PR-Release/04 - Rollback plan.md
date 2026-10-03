---
title: "Rollback plan"
format: prompt
archetype: instruction
domain: git-release
tags:
  - git
  - release
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
expected_output: "ready-to-use Git/release artifact"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Rollback plan

## When to use it

For a risky release.

## Copy-ready prompt

```text
Prepare the rollback for this release.

Define:
- trigger signal;
- decision owner;
- steps;
- code;
- DB;
- cache;
- queues;
- feature flags;
- possible forward-only data;
- post-rollback validation;
- communication;
- risks of the rollback itself.

Output: a ready-to-use Git/release artifact.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A ready-to-use Git/release artifact.
