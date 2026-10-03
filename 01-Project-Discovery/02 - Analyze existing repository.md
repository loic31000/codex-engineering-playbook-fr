---
title: "Analyze an existing repository"
format: prompt
archetype: workflow
domain: discovery
tags:
  - brownfield
  - repo-analysis
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
expected_output: "reliable map of the codebase and its risks"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Analyze an existing repository

## When to use it

When taking over an existing codebase and you want to understand its structure before modifying it.

## Copy-ready prompt

```text
Analyze this repository as a senior developer who must take it over without breaking its behavior.

Do not modify anything.

Identify:
- language(s) and frameworks;
- repository structure;
- applications/packages;
- entry points;
- actual architecture;
- modules and responsibilities;
- important dependencies;
- database and migrations;
- APIs/contracts;
- authentication/authorization;
- tests;
- CI/CD;
- configuration/environments;
- observability;
- visible technical debt;
- security-sensitive areas;
- existing documentation;
- inconsistencies between documentation and code.

Clearly separate:
- observed facts;
- assumptions;
- unknown areas;
- risks.

Finish with a repository map and a list of the 10 files/directories to understand first.

Output: a reliable map of the codebase and its risks.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A reliable map of the codebase and its risks.

## Control points

- [ ] No modifications
- [ ] Facts separated from assumptions
- [ ] Actual architecture described, not merely inferred
