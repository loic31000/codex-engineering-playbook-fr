---
title: "Compress project context"
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

# Compress project context

## When to use it

When the conversation becomes too long.

## Copy-ready prompt

```text
Transform this context into a compact briefing for a new Codex session.

Keep only:
- objective;
- current state;
- confirmed decisions;
- assumptions;
- relevant architecture;
- relevant files;
- constraints;
- tests;
- open issues;
- next action.

Remove:
- historical discussion;
- rejected alternatives with no remaining consequence;
- repetition;
- unnecessary details.

Output: a more robust prompt or workflow.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A more robust prompt or workflow.
