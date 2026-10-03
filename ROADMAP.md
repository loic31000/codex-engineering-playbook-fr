# Roadmap

La roadmap n’est pas un engagement de dates. Elle sert à choisir les prochains domaines à enrichir.

## Priorité 1 — Stabiliser l’existant

- [ ] Tester les prompts les plus utilisés avec Codex.
- [ ] Promouvoir les bons prompts de `draft` vers `testing`.
- [ ] Documenter les échecs ou limites rencontrés.
- [ ] Fusionner les prompts trop proches.
- [ ] Réduire les prompts inutilement longs.
- [ ] Créer quelques exemples de sorties de référence.

## Priorité 2 — Frontend & Design avancé

- [ ] Audit design system existant.
- [ ] Composition de pages complexes.
- [ ] Dashboard et visualisation de données.
- [ ] Design mobile natif.
- [ ] Internationalisation UI.
- [ ] Design pour permissions et rôles complexes.
- [ ] Audit de cohérence cross-écrans.
- [ ] Migration/refonte design system.
- [ ] Storybook et documentation composants.
- [ ] Tests visuels et régression visuelle.

## Priorité 3 — Mobile

- [ ] Architecture mobile.
- [ ] Navigation native.
- [ ] Offline-first.
- [ ] Synchronisation.
- [ ] Permissions appareil.
- [ ] Notifications.
- [ ] Performance mobile.
- [ ] Release App Store / Play Store.
- [ ] Accessibilité mobile.

## Priorité 4 — DevOps / SRE

- [ ] Design CI/CD.
- [ ] Infrastructure as Code.
- [ ] Environnements.
- [ ] Observabilité.
- [ ] SLO/SLI.
- [ ] Incident response.
- [ ] Capacity planning.
- [ ] Disaster recovery.
- [ ] Blue/green et canary.
- [ ] Gestion de configuration.

## Priorité 5 — IA / LLM

- [ ] Architecture application LLM.
- [ ] RAG.
- [ ] Evaluation de prompts.
- [ ] Evaluation de réponses.
- [ ] Guardrails.
- [ ] Tool calling.
- [ ] Agents.
- [ ] Mémoire.
- [ ] Sécurité prompt injection.
- [ ] Coûts tokens au niveau architecture, pas User Story.
- [ ] Observabilité LLM.

## Priorité 6 — Data Engineering

- [ ] ETL/ELT.
- [ ] Data quality.
- [ ] Schémas et contrats.
- [ ] Pipelines.
- [ ] Batch vs streaming.
- [ ] Lineage.
- [ ] Backfill.
- [ ] Analytics engineering.
- [ ] Data warehouse.
- [ ] Gouvernance des données.

## Priorité 7 — Sécurité avancée

- [ ] OAuth/OIDC review.
- [ ] Passkeys.
- [ ] Cryptographie appliquée.
- [ ] Secure SDLC.
- [ ] Threat modeling STRIDE ciblé.
- [ ] Supply-chain avancée.
- [ ] Secrets rotation.
- [ ] Security incident response.
- [ ] Abuse cases.
- [ ] API security avancée.

## Priorité 8 — Architecture avancée

- [ ] Event-driven.
- [ ] Distributed systems.
- [ ] CQRS.
- [ ] Event sourcing.
- [ ] Architecture multi-région.
- [ ] Architecture offline/sync.
- [ ] Migration monolithe → services.
- [ ] Architecture review de systèmes legacy.

## Backlog libre

Ajoute ici les idées avant de créer une Issue :

- [ ] ...


## V0.2 — recommandations de l'audit 2026

Réalisé structurellement :

- [x] contrat de sortie dans les prompts copiables ;
- [x] séparation `format` / `archetype` ;
- [x] métadonnées de validation et risque ;
- [x] sécurité agentique / prompt injection ;
- [x] frontend : screenshot/référence, i18n/RTL, boucle de correction visuelle ;
- [x] clarification WCAG conformité vs bonnes pratiques ;
- [x] glossaire technique ;
- [x] protocole de tests et revalidation.

À valider par l'usage :

- [ ] tester en priorité Implémentation ;
- [ ] puis Review / convergence ;
- [ ] puis Sécurité / Privacy ;
- [ ] puis Frontend / Design / UX ;
- [ ] puis Specs / Stories ;
- [ ] constituer un premier noyau de 20–30 prompts `stable` ;
- [ ] ne pas promouvoir artificiellement les autres prompts sans résultats réels.
