---
title: "Extract decisions from a conversation"
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

# Extract decisions from a conversation

## When to use it

After a long session.

## Copy-ready prompt

```text
From this conversation, extract only durable decisions.

For each:
- decision;
- state: confirmed / assumption / undecided;
- rationale;
- consequence;
- document to update;
- possible need for an ADR.

Do not turn a suggestion into a confirmed decision.

Output: a more robust prompt or workflow.
```

## Expected output

A more robust prompt or workflow.
