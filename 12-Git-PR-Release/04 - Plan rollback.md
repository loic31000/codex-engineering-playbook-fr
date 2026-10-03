---
titre: "Plan de rollback"
format: prompt
archetype: instruction
domaine: git-release
tags:
  - git
  - release
statut: draft
version: "0.2.0"
langue: fr-FR
outils:
  - codex
tests_reels: 0
cas_reussis: 0
modeles_testes: []
derniere_validation: null
derniere_revision: 2026-10-03
entrees_requises:
  - contexte-fourni
sortie_attendue: "artefact Git/release prêt à l'emploi"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Plan de rollback

## Quand l'utiliser

Pour une release risquée.

## Prompt prêt à copier

```text
Prépare le rollback de cette release.

Définis :
- signal déclencheur ;
- décisionnaire ;
- étapes ;
- code ;
- DB ;
- cache ;
- queues ;
- feature flags ;
- data forward-only éventuelle ;
- validation après rollback ;
- communication ;
- risques du rollback lui-même.

Sortie : artefact Git/release prêt à l'emploi.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
