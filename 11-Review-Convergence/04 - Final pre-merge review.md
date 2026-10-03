---
title: "Final pre-merge review"
format: prompt
archetype: checklist
domain: review-convergence
tags:
  - review
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
expected_output: "prioritized and actionable review"
risk_level: medium
external_actions: false
sensitive_data: do_not_provide
---

# Final pre-merge review

## When to use it

As the last control before merge.

## Copy-ready prompt

```text
Perform a final merge review.

Verify:
- Story was READY and implemented;
- acceptance criteria satisfied;
- tests;
- lint/typecheck/build when applicable;
- security;
- migrations;
- API;
- documentation;
- ADRs;
- TODO/FIXME;
- logs/secrets;
- focused diff;
- rollback when necessary.

Reply:
- MERGEABLE;
or
- BLOCKED with precise blockers.

Do not return MERGEABLE if a required verification is unknown.

Output: a prioritized and actionable review.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritized and actionable review.
