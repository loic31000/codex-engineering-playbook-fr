---
titre: "Créer une stratégie de tests"
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

# Créer une stratégie de tests

## Quand l'utiliser

Au niveau projet ou grosse feature.

## Prompt prêt à copier

```text
Définis une stratégie de tests proportionnée au risque.

Répartis :
- unit ;
- integration ;
- contract ;
- E2E ;
- accessibility ;
- security ;
- performance si nécessaire.

Pour chaque type :
- objectif ;
- ce qu'il couvre ;
- ce qu'il ne doit pas couvrir ;
- vitesse ;
- environnement ;
- données ;
- déclenchement CI.

Privilégie la couverture des exigences et risques plutôt qu'un pourcentage arbitraire.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
