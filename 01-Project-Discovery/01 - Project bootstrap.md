---
title: "Project bootstrap"
format: prompt
archetype: workflow
domain: discovery
tags:
  - discovery
  - bootstrap
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
expected_output: "complete but concise project map with explicit uncertainties"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Project bootstrap

## When to use it

At the very beginning of a new project or when the existing context is insufficient.

## Copy-ready prompt

```text
Act as a product and software architect responsible for framing this project before any implementation.

Run a progressive interview in English.

Work in groups of no more than 3 to 5 questions.

Cover only relevant domains:
- product problem;
- users;
- scope and out of scope;
- UX/UI;
- architecture;
- frontend/backend;
- data;
- authentication/authorization;
- security and privacy;
- integrations;
- infrastructure;
- observability;
- testing;
- Git/CI;
- development workflow.

For each important decision, use one state:
- confirmed;
- assumption;
- undecided;
- N/A.

Never invent a missing decision.
If you recommend something, mark it as a proposal until I validate it.

At the end, produce:
1. confirmed decisions;
2. assumptions;
3. still-undecided decisions;
4. risks;
5. documents to create;
6. blockers before specification.
```

## Expected output

A complete but concise project map with explicit uncertainties.

## Control points

- [ ] No implementation started
- [ ] No assumption turned into a decision
- [ ] Security risks identified
