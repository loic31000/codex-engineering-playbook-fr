---
title: "Internationalization, RTL, and long text"
format: prompt
archetype: checklist
domain: frontend-design-ux
tags:
  - frontend
  - ux
  - i18n
  - rtl
status: draft
version: "0.1.0"
source_branch: main
source_version: "0.1.0"
language: en
tools:
  - codex
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
last_revision: 2026-10-03
required_inputs:
  - interface-or-components
  - target-locales-if-known
expected_output: "i18n and RTL risks with corrections and test scenarios"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Internationalization, RTL, and long text

## When to use it

To verify that an interface remains usable across languages, long text, or RTL direction.

## Copy-ready prompt

```text
Review this interface for internationalization.

Verify:
- non-externalized strings;
- fragile concatenations;
- plurals, dates, numbers, currencies, and time zones;
- text expansion;
- long labels and buttons;
- truncation;
- flexible layouts;
- logical order and RTL direction;
- directional icons;
- forms;
- tables and dense content.

For each finding:
- affected locale or scenario;
- evidence;
- user impact;
- correction;
- verification test.

Do not invent target locales: mark them "to clarify" if they affect the decision.
```

## Expected output

A directly actionable i18n/RTL review.
