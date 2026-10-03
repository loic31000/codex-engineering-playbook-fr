---
title: "Identify non-negotiable constraints"
format: prompt
archetype: instruction
domain: discovery
tags:
  - constraints
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
expected_output: "clear constraints contract"
risk_level: low
external_actions: false
sensitive_data: do_not_provide
---

# Identify non-negotiable constraints

## When to use it

When you want to distinguish real constraints from preferences.

## Copy-ready prompt

```text
Analyze the constraints expressed for this project.

Classify each as:
- regulatory requirement;
- business requirement;
- technical constraint;
- organizational constraint;
- compatibility constraint;
- security constraint;
- preference only.

For each constraint:
- restate it precisely;
- identify its source;
- state what it forbids;
- state what it leaves open;
- flag any contradiction.

Finish with a "non-negotiable" list separated from preferences.

Output: a clear constraints contract.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A clear constraints contract.

## Control points

- [ ] Preferences separated from requirements
- [ ] Contradictions visible
