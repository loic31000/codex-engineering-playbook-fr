---
title: "Final visual review"
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

# Final visual review

## When to use it

Before merging a frontend screen.

## Copy-ready prompt

```text
Review the final interface as design QA.

Verify:
- design-system consistency;
- spacing;
- alignments;
- typography;
- colors;
- contrast;
- responsive behavior;
- states;
- interactions;
- keyboard/focus;
- errors;
- loading/empty states;
- density;
- mobile;
- polish.

Separate UX/accessibility blockers from purely aesthetic details.

Output: a prioritized and actionable review.

If missing information materially changes the result, mark it "to clarify" instead of inventing it.
```

## Expected output

A prioritized and actionable review.
