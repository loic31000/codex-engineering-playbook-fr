---
titre: "Concevoir les E2E critiques"
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

# Concevoir les E2E critiques

## Quand l'utiliser

Pour parcours utilisateur essentiels.

## Prompt prêt à copier

```text
À partir des critères d'acceptation, sélectionne les parcours qui méritent un E2E.

Pour chaque scénario :
- préconditions ;
- étapes utilisateur ;
- résultat visible ;
- assertions ;
- données ;
- cleanup ;
- erreurs ;
- navigateur/device si pertinent.

Évite de dupliquer toute la suite unitaire en E2E.

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
