---
titre: "Vérifier la couverture des exigences"
format: prompt
archetype: checklist
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

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
