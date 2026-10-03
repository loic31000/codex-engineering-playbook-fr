---
title: "Story Ready Review"
format: prompt
archetype: checklist
domain: specifications
tags:
  - spec
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
expected_output: "reasoned readiness decision"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Story Ready Review

## When to use it

Immediately before implementation.

## Copy-ready prompt

```text
Act as the Definition of Ready gatekeeper.

Evaluate this Story without coding.

Verify:
- objective;
- scope;
- acceptance criteria;
- edge cases;
- dependencies;
- open decisions;
- impacted architecture;
- data/migrations;
- security/privacy;
- UX/UI;
- APIs/contracts;
- test strategy;
- Story size.

Reply only with:
- READY or BLOCKED;
- blockers;
- non-blocking points;
- required decisions/questions;
- recommendation: formal plan required or not.

Output: a reasoned readiness decision.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A reasoned readiness decision.
