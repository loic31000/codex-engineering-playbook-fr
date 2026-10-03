---
title: "Split a large feature"
format: prompt
archetype: workflow
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
expected_output: "implementable feature breakdown"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Split a large feature

## When to use it

When a Story or feature is too large.

## Copy-ready prompt

```text
Split this feature into small, coherent, and verifiable increments.

Constraints:
- each Story must provide value or an observable outcome;
- minimize circular dependencies;
- allow reasonably sized PRs;
- avoid Stories that are only "backend" and then only "frontend" unless there is a real technical necessity;
- identify technical foundations when they must precede user value;
- preserve traceability to the original feature.

For each Story:
- objective;
- main acceptance criteria;
- dependencies;
- recommended order;
- risk.

Output: an implementable breakdown of the feature.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

An implementable breakdown of the feature.
