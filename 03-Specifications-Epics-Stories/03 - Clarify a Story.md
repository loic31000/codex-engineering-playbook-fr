---
title: "Clarify a Story"
format: prompt
archetype: instruction
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
expected_output: "Story with important ambiguities explicitly addressed"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Clarify a Story

## When to use it

When the Story seems vague or contains words such as fast, intuitive, secure, and so on.

## Copy-ready prompt

```text
Analyze this Story and do not implement it.

Find:
- ambiguities;
- subjective terms;
- missing decisions;
- contradictory behaviors;
- edge cases;
- hidden dependencies;
- unspoken security/data requirements;
- non-testable acceptance criteria.

Then ask only the questions that could change expected behavior, architecture, security, or scope.

After clarification, propose a revised version without inventing answers.

Output: a Story with important ambiguities explicitly addressed.
```

## Expected output

A Story with important ambiguities explicitly addressed.
