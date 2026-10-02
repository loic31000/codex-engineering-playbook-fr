---
titre: "Créer un test de régression"
type: prompt
tags:
  - testing
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
