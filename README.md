# Prompt & Skill Library for Codex

A personal and evolving library of **prompts, workflows, skills, checklists, and software engineering references**, designed for use in **Obsidian** and versioned on **GitHub**.

The entire repository is **Markdown** and **English**.

> English branch: `en`. The French `main` branch remains the source of truth. English files should track their French source version when applicable.

## Goal

The goal is not to collect "magic prompts."

The goal is to progressively build a library of **engineering workflows tested with Codex** covering the full development lifecycle:

```text
Idea
→ discovery
→ product
→ specification
→ architecture
→ UX/UI/design
→ security
→ planning
→ implementation
→ testing
→ review
→ convergence
→ PR
→ release
→ maintenance
```

## Using it in Obsidian

Simply open the repository root as an Obsidian vault.

Start with:

- [[00-Home/00 - Start here]]
- [[00-Home/01 - Daily workflow]]
- [[00-Home/03 - Choose the right prompt]]
- [[00-Home/04 - Full index]]
- [[00-Home/05 - Prompt lifecycle]]
- [[00-Home/06 - Library conventions]]

## Statuses

Each prompt can evolve through four states:

```text
draft
  ↓
testing
  ↓
stable
  ↓
deprecated
```

### `draft`

The prompt exists but has not yet been sufficiently proven.

### `testing`

The prompt is currently being used on real cases with Codex.

### `stable`

The prompt has produced satisfactory results on multiple real cases and its limitations are understood.

### `deprecated`

The prompt is kept for historical purposes but should no longer be used.

## Promotion rule for `stable`

A prompt should normally become `stable` only after:

- at least 3 real-world uses;
- no known critical issue;
- sufficiently reproducible output;
- instructions that remain understandable without hidden context;
- verification that it does not push Codex to silently expand scope.

## Structure

```text
00-Home/
01-Project-Discovery/
02-Product-Scope/
03-Specifications-Epics-Stories/
04-Architecture-Stack/
05-Data-API-Integrations/
06-Frontend-Design-UX/
07-Security-Privacy/
08-Planning-Tasks/
09-Implementation/
10-Testing-Quality/
11-Review-Convergence/
12-Git-PR-Release/
13-Debug-Maintenance/
14-Documentation/
15-Meta-Prompting/
16-Checklists-References/
```

Frontend and design include dedicated prompts for:

- frontend architecture;
- visual direction;
- design system;
- tokens;
- screens;
- components;
- navigation;
- responsive design;
- accessibility;
- forms;
- loading/empty/error states;
- UX writing;
- motion;
- Core Web Vitals;
- visual QA;
- dark mode;
- final frontend review.

## Philosophy

A good working prompt should encourage:

- a clear objective;
- relevant context;
- explicit scope;
- known constraints;
- expected output;
- success criteria;
- verification;
- a stop condition when an important decision is missing.

The library avoids as much as possible:

- mega-prompts;
- micromanaging reasoning;
- decisions invented by the agent;
- vague criteria;
- prompts that confuse code generation with actual task completion.

## Contributing

See [[CONTRIBUTING]].

## Roadmap

See [[ROADMAP]].

## License

MIT — see [[LICENSE]].

## V0.2 evolution — October 2026 audit

V0.2 applies the recommendations from the library's in-depth audit:

- output contract integrated into the copyable prompt block;
- metadata separating `format` and `archetype`;
- structured inputs, risk level, and validation history;
- stronger uncertainty handling without turning files into mega-prompts;
- agentic security and prompt injection;
- expanded frontend coverage: visual references, i18n/RTL, and screenshot → compare → fix loop;
- WCAG: separation of compliance failure / unverifiable point / best practice;
- real-world testing protocol and revalidation of `stable` prompts;
- English technical glossary.

Prompts remain `draft` until they accumulate real-world evidence. A structural revision is not empirical validation.
