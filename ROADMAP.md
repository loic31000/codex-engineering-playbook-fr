# Roadmap

The roadmap is not a date commitment. It helps choose the next domains to expand.

## Priority 1 — Stabilize what already exists

- [ ] Test the most-used prompts with Codex.
- [ ] Promote good prompts from `draft` to `testing`.
- [ ] Document observed failures or limitations.
- [ ] Merge prompts that are too similar.
- [ ] Reduce unnecessarily long prompts.
- [ ] Create a few reference output examples.

## Priority 2 — Advanced Frontend & Design

- [ ] Audit an existing design system.
- [ ] Compose complex pages.
- [ ] Dashboard and data visualization.
- [ ] Native mobile design.
- [ ] UI internationalization.
- [ ] Design for complex permissions and roles.
- [ ] Cross-screen consistency audit.
- [ ] Design system migration/redesign.
- [ ] Storybook and component documentation.
- [ ] Visual testing and visual regression.

## Priority 3 — Mobile

- [ ] Mobile architecture.
- [ ] Native navigation.
- [ ] Offline-first.
- [ ] Synchronization.
- [ ] Device permissions.
- [ ] Notifications.
- [ ] Mobile performance.
- [ ] App Store / Play Store release.
- [ ] Mobile accessibility.

## Priority 4 — DevOps / SRE

- [ ] CI/CD design.
- [ ] Infrastructure as Code.
- [ ] Environments.
- [ ] Observability.
- [ ] SLO/SLI.
- [ ] Incident response.
- [ ] Capacity planning.
- [ ] Disaster recovery.
- [ ] Blue/green and canary.
- [ ] Configuration management.

## Priority 5 — AI / LLM

- [ ] LLM application architecture.
- [ ] RAG.
- [ ] Prompt evaluation.
- [ ] Response evaluation.
- [ ] Guardrails.
- [ ] Tool calling.
- [ ] Agents.
- [ ] Memory.
- [ ] Prompt injection security.
- [ ] Token costs at the architecture level, not in User Stories.
- [ ] LLM observability.

## Priority 6 — Data Engineering

- [ ] ETL/ELT.
- [ ] Data quality.
- [ ] Schemas and contracts.
- [ ] Pipelines.
- [ ] Batch vs streaming.
- [ ] Lineage.
- [ ] Backfill.
- [ ] Analytics engineering.
- [ ] Data warehouse.
- [ ] Data governance.

## Priority 7 — Advanced Security

- [ ] OAuth/OIDC review.
- [ ] Passkeys.
- [ ] Applied cryptography.
- [ ] Secure SDLC.
- [ ] Focused STRIDE threat modeling.
- [ ] Advanced supply chain.
- [ ] Secret rotation.
- [ ] Security incident response.
- [ ] Abuse cases.
- [ ] Advanced API security.

## Priority 8 — Advanced Architecture

- [ ] Event-driven.
- [ ] Distributed systems.
- [ ] CQRS.
- [ ] Event sourcing.
- [ ] Multi-region architecture.
- [ ] Offline/sync architecture.
- [ ] Monolith → services migration.
- [ ] Legacy system architecture review.

## Free backlog

Add ideas here before creating an Issue:

- [ ] ...

## V0.2 — 2026 audit recommendations

Structurally completed:

- [x] output contract in copyable prompts;
- [x] separation of `format` / `archetype`;
- [x] validation and risk metadata;
- [x] agentic security / prompt injection;
- [x] frontend: screenshot/reference, i18n/RTL, visual correction loop;
- [x] WCAG clarification: compliance vs best practices;
- [x] technical glossary;
- [x] testing and revalidation protocol.

To validate through real usage:

- [ ] test Implementation first;
- [ ] then Review / convergence;
- [ ] then Security / Privacy;
- [ ] then Frontend / Design / UX;
- [ ] then Specs / Stories;
- [ ] build a first core of 20–30 `stable` prompts;
- [ ] do not artificially promote other prompts without real results.
