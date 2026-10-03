---
titre: "Créer un test de régression"
format: prompt
archetype: workflow
domaine: tests-qualite
tags:
  - testing
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
sortie_attendue: "stratégie ou suite de tests alignée sur les risques"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Créer un test de régression

## Quand l'utiliser

Après correction d'un bug.

## Prompt prêt à copier

```text
À partir du bug reproduit, écris d'abord le scénario de régression minimal.

Le test doit :
- échouer avant le correctif ;
- réussir après ;
- refléter la cause ou le comportement observable ;
- éviter les détails d'implémentation inutiles.

Ensuite seulement, propose le correctif minimal.

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
