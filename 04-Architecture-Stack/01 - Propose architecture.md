---
title: "Propose an architecture"
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

# Propose an architecture

## When to use it

When the architecture has not yet been chosen.

## Copy-ready prompt

```text
Based on the project's confirmed constraints, propose 2 to 4 plausible architectures.

For each option:
- structure;
- advantages;
- disadvantages;
- operational complexity;
- testing impact;
- security impact;
- evolvability impact;
- cognitive cost for the team;
- risks.

Then indicate which seems most suitable AND why, but mark it as a recommendation rather than a decision.

Prefer the simplest solution that genuinely satisfies the constraints.

Output: a structured architecture analysis or decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A structured architecture analysis or decision.
