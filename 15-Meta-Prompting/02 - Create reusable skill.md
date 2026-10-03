---
title: "Create a reusable skill"
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

# Create a reusable skill

## When to use it

When a workflow recurs often.

## Copy-ready prompt

```text
Transform this workflow into a reusable Markdown skill.

Structure:
- name;
- triggering description;
- objective;
- when to use it;
- required context;
- preconditions;
- procedure;
- constraints;
- output;
- verification;
- stop/escalation conditions.

The skill must focus on one workflow.
Do not put all project documentation into it.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A more robust prompt or workflow.
