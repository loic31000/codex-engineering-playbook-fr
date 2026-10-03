---
title: "Architecture review"
format: prompt
archetype: checklist
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

# Architecture review

## When to use it

After a proposal or on an existing project.

## Copy-ready prompt

```text
Review this architecture as a critical architect.

Evaluate:
- module cohesion;
- coupling;
- dependencies;
- dependency direction;
- business boundaries;
- persistence;
- contracts;
- security;
- observability;
- testability;
- deployment;
- failure modes;
- accidental complexity.

Identify:
- risks;
- over-engineering;
- likely debt;
- unjustified elements;
- decisions requiring an ADR.

Do not propose microservices by default.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
