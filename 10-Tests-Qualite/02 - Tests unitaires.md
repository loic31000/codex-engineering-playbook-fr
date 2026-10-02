---
titre: "Écrire les tests unitaires pertinents"
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

# Écrire les tests unitaires pertinents

## Quand l'utiliser

Après ou pendant implémentation d'une unité métier.

## Prompt prêt à copier

```text
Analyse ce code et écris uniquement les tests unitaires qui apportent une vraie valeur.

Couvre :
- règles métier ;
- limites ;
- erreurs ;
- branches significatives ;
- invariants.

Évite :
- tests qui recopient l'implémentation ;
- mocks excessifs ;
- tests de framework ;
- assertions fragiles.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
