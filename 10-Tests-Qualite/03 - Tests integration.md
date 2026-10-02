---
titre: "Concevoir les tests d'intégration"
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
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
