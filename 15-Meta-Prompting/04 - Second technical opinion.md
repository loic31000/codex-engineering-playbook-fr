---
title: "Get a second technical opinion"
format: prompt
archetype: workflow
domain: meta-prompting
tags:
  - prompting
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
expected_output: "more robust prompt or workflow"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Get a second technical opinion

## When to use it

For an important decision.

## Copy-ready prompt

```text
Analyze this decision as if you had to challenge an already accepted proposal.

Look for:
- fragile assumptions;
- undervalued alternatives;
- cognitive costs;
- complexity;
- security risks;
- operational concerns;
- lock-in;
- migration;
- testability.

Do not disagree for the sake of disagreeing.
Explicitly say when the current decision is reasonable.

Output: a more robust prompt or workflow.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A more robust prompt or workflow.
