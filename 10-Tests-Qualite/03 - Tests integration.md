---
titre: "Concevoir les tests d'intégration"
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

# Concevoir les tests d'intégration

## Quand l'utiliser

Pour DB/API/services intégrés.

## Prompt prêt à copier

```text
Conçois les tests d'intégration nécessaires à cette feature.

Couvre les frontières réelles :
- DB ;
- API ;
- queue ;
- filesystem ;
- service externe simulé ;
- auth ;
- transactions.

Définis :
- setup ;
- fixtures ;
- isolation ;
- cleanup ;
- cas succès ;
- cas erreurs ;
- concurrence si pertinente.

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
