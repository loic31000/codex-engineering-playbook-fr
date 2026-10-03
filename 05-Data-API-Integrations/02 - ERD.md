---
title: "Prepare an ERD"
format: prompt
archetype: template
domain: data-api
tags:
  - data
  - api
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
expected_output: "explicit and verifiable data/API design"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Prepare an ERD

## When to use it

When you want to formalize relationships before a migration.

## Copy-ready prompt

```text
Transform this business model into an ERD description.

Include:
- entities;
- PKs;
- FKs;
- relationships;
- cardinalities;
- important constraints;
- association tables;
- tenant ownership when applicable.

Add a section for:
- integrity risks;
- normalization decisions;
- potential indexes to measure;
- points to clarify.

Output: explicit and verifiable data/API design.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An explicit and verifiable data/API design.
