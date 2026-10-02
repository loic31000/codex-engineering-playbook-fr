---
titre: "Vérifier la couverture des exigences"
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

# Vérifier la couverture des exigences

## Quand l'utiliser

Avant de déclarer une Story terminée.

## Prompt prêt à copier

```text
Construis une matrice :

Acceptance Criterion
→ méthode de vérification
→ test(s)
→ statut

Identifie :
- AC sans test/vérification ;
- tests sans exigence claire ;
- edge cases non couverts ;
- sécurité non couverte ;
- dépendance excessive au test manuel.

Ne confonds pas code coverage et requirements coverage.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
