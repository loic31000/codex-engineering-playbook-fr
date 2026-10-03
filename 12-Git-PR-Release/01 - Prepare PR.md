---
title: "Prepare a Pull Request"
format: prompt
archetype: checklist
domain: git-release
tags:
  - git
  - release
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
expected_output: "ready-to-use Git/release artifact"
risk_level: high
external_actions: false
sensitive_data: do_not_provide
---

# Prepare a Pull Request

## When to use it

After tests and convergence.

## Copy-ready prompt

```text
Prepare the content for a clear PR.

Include:
- why;
- what changes;
- what does not change;
- associated Story/Epic;
- important technical decisions;
- migrations;
- security;
- tests run;
- screenshots/visual QA for frontend work;
- risks;
- rollback when necessary;
- reviewer checklist.

Stay concise and make review easy.

Output: a ready-to-use Git/release artifact.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A ready-to-use Git/release artifact.
