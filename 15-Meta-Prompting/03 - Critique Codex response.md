---
title: "Critique a Codex response"
format: prompt
archetype: checklist
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

# Critique a Codex response

## When to use it

When you want an independent second pass.

## Copy-ready prompt

```text
Act as an independent reviewer.

Evaluate this Codex response for:
- compliance with the request;
- unsupported facts;
- hidden assumptions;
- scope creep;
- security;
- architecture;
- testability;
- omissions;
- output quality.

Do not rewrite immediately.
Start with the most important problems, then propose corrections.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A more robust prompt or workflow.
