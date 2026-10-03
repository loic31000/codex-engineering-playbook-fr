---
titre: "Créer une stratégie de tests"
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

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
