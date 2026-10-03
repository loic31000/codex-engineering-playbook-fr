---
title: "Improve acceptance criteria"
format: prompt
archetype: template
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
expected_output: "measurable acceptance criteria"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Improve acceptance criteria

## When to use it

When criteria are too vague or look like technical tasks.

## Copy-ready prompt

```text
Review the acceptance criteria for this Story.

For each criterion:
- verify that it describes observable behavior or an observable outcome;
- verify that it is testable;
- remove duplicates;
- identify missing criteria;
- add errors/permissions/edge cases that are genuinely necessary.

Use Given/When/Then when it improves precision, without forcing it artificially.

Do not change the business scope.

Output: measurable acceptance criteria.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

Measurable acceptance criteria.
