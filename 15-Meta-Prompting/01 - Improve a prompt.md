---
title: "Improve a prompt"
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

# Improve a prompt

## When to use it

When a prompt is too vague or too long.

## Copy-ready prompt

```text
Critique this prompt before rewriting it.

Analyze:
- objective;
- context;
- ambiguities;
- constraints;
- expected output;
- success criteria;
- unnecessary information;
- contradictions;
- scope-creep risks.

Then produce an improved version that is:
- shorter;
- more precise;
- outcome-oriented;
- free from reasoning micromanagement;
- equipped with escalation conditions when a decision is missing.
```

## Expected output

A more robust prompt or workflow.
