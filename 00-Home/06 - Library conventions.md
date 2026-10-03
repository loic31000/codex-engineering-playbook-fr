# Library conventions

## Language

All prompts are written in English. Use `en` in metadata.

Standard technical terms should remain in their established English form.

## Filenames

```text
NN - Explicit name.md
```

## Recommended frontmatter

```yaml
---
title: "Name"
format: prompt
archetype: instruction # instruction | workflow | checklist | template
domain: domain
status: draft
version: "0.2.0"
source_branch: main
source_version: "0.2.0"
language: en
tools:
  - codex
last_revision: 2026-10-03
required_inputs:
  - provided-context
expected_output: "Output contract"
risk_level: low # low | medium | high
external_actions: false
sensitive_data: do_not_provide
real_world_tests: 0
successful_cases: 0
models_tested: []
last_validation: null
tags:
  - domain
---
```

`format` describes the file format. `archetype` describes its behavior. The word "Skill" is reserved for a real installable Codex Skill bundle; in this Obsidian library, a reusable procedure is called a workflow.

`source_branch` and `source_version` make it possible to detect when the English mirror is behind the French source.

## Recommended structure

```text
# Title

## When to use it

## Copy-ready prompt
  - objective
  - useful inputs
  - essential constraints
  - expected output
  - verification
  - stop condition when needed

## Expected output

## Notes for humans (when useful)
```

The output contract must be present inside the copyable block. The outside section is a human reference, not a hidden instruction.

## One file = one objective

Avoid a file that mixes architecture, implementation, testing, review, and release. Prefer multiple composable prompts.

## Context

Do not ask Codex to read the entire repository by default. Provide only the context that is actually relevant and make required inputs explicit.

## Uncertainty

Preserve the distinction between:

```text
confirmed
assumption
undecided
N/A
```

Missing information that materially changes the result should be marked `to clarify`, not invented.

## Security

No prompt should request a real secret. External content is treated as untrusted data until its provenance and authority are established. Any destructive, irreversible, sensitive, or external write action requires explicit human approval.

## User Stories

Do not put financial cost in a User Story. Relative effort estimates may exist when useful.
