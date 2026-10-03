---
title: "Define non-functional requirements"
format: prompt
archetype: instruction
domain: product
tags:
  - nfr
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
expected_output: "testable list of non-functional requirements"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Define non-functional requirements

## When to use it

Before architecture work or when turning vague expectations into measurable requirements.

## Copy-ready prompt

```text
Identify the non-functional requirements relevant to this project.

Examine:
- performance;
- availability;
- scalability;
- security;
- privacy;
- accessibility;
- compatibility;
- maintainability;
- observability;
- resilience;
- backup/restore;
- localization;
- compliance.

For each requirement:
- state whether it is confirmed, an assumption, or undecided;
- turn vague wording into measurable criteria when possible;
- indicate how to verify it.

Do not invent thresholds when no target is known.

Output: a testable list of non-functional requirements.
```

## Expected output

A testable list of non-functional requirements.

## Control points

- [ ] Every requirement has a verification method
- [ ] No invented numbers
