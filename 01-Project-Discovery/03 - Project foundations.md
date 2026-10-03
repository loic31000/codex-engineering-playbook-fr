---
title: "Project foundations"
format: prompt
archetype: checklist
domain: discovery
tags:
  - governance
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
expected_output: "short, actionable, and verifiable project constitution"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Project foundations

## When to use it

When you want to define the non-negotiable rules that will guide Codex and developers.

## Copy-ready prompt

```text
Using the project context, write a short and operational development constitution.

It must define non-negotiable rules for:
- specification before implementation;
- scope control;
- architecture;
- security;
- data and migrations;
- dependencies;
- testing;
- documentation;
- quality;
- Definition of Ready;
- Definition of Done;
- review;
- merge.

Avoid vague rules such as "write good code."

Each rule must be:
- observable;
- applicable;
- verifiable;
- concise enough.

Distinguish:
- mandatory rule;
- recommendation;
- decision requiring human validation.

Output: a short, actionable, and verifiable project constitution.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A short, actionable, and verifiable project constitution.

## Control points

- [ ] Concrete rules
- [ ] No micromanagement
- [ ] Clear mandatory/recommended distinction
