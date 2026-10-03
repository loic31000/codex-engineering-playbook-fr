---
title: "Define repository structure"
format: prompt
archetype: workflow
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

# Define repository structure

## When to use it

When the codebase needs a clear organization.

## Copy-ready prompt

```text
Propose a repository structure suited to the validated architecture.

For each main directory:
- responsibility;
- what may belong there;
- what must not belong there;
- allowed dependencies.

Favor:
- discoverability;
- proximity between code and tests;
- visible boundaries;
- simple conventions.

Avoid deep directory trees without value.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
