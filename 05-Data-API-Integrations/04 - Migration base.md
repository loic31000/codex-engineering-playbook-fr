---
titre: "Planifier une migration de base"
format: prompt
archetype: workflow
domaine: data-api
tags:
  - data
  - api
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
sortie_attendue: "design de données/API explicite et vérifiable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Planifier une migration de base

## Quand l'utiliser

Avant une modification de schéma risquée.

## Prompt prêt à copier

```text
Prépare un plan de migration de données sûr.

Inclure :
- état actuel ;
- état cible ;
- migration de schéma ;
- migration de données ;
- compatibilité pendant déploiement ;
- ordre des étapes ;
- backfill ;
- contraintes/index ;
- rollback ou stratégie forward-only ;
- impact disponibilité ;
- vérifications avant/après ;
- tests.

Évite les migrations destructrices en une seule étape si le système est en production.

Sortie : design de données/API explicite et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
