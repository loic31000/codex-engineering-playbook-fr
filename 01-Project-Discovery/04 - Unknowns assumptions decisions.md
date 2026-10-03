---
title: "Map unknowns, assumptions, and decisions"
format: prompt
archetype: instruction
domain: discovery
tags:
  - decision-management
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
expected_output: "clear and actionable knowledge register"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Map unknowns, assumptions, and decisions

## When to use it

When the project seems to be moving forward with many implicit assumptions.

## Copy-ready prompt

```text
Analyze the available context and build four distinct lists:

1. CONFIRMED
Facts and decisions explicitly established.

2. ASSUMPTIONS
Elements used to move forward but not yet validated.

3. UNDECIDED
Relevant decisions that have not yet been made.

4. N/A
Topics explicitly not applicable.

For each assumption or undecided decision, indicate:
- potential impact;
- risk level;
- latest point by which it must be resolved;
- exact question to ask.

Do not create any new decision.

Output: a clear and actionable knowledge register.
```

## Expected output

A clear and actionable knowledge register.

## Control points

- [ ] No mixing assumptions and decisions
- [ ] Every undecided item has a precise question
