---
titre: "Écrire les tests unitaires pertinents"
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

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
