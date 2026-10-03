---
titre: "Tests composants frontend"
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

# Tests composants frontend

## Quand l'utiliser

Pour composants UI avec logique et états.

## Prompt prêt à copier

```text
Définis les tests utiles pour ces composants.

Priorise :
- comportement utilisateur ;
- accessibilité ;
- états ;
- erreurs ;
- interactions ;
- callbacks ;
- responsive logique si testable.

Évite de tester :
- détails CSS triviaux ;
- structure DOM exacte sans raison ;
- internals du framework.

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
