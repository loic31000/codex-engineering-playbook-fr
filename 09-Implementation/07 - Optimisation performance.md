---
titre: "Optimiser après mesure"
format: prompt
archetype: workflow
domaine: implementation
tags:
  - implementation
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
sortie_attendue: "implémentation contrôlée, testée et dans le scope"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Optimiser après mesure

## Quand l'utiliser

Quand un bottleneck a été observé.

## Prompt prêt à copier

```text
À partir des mesures/profiling fournis, propose puis implémente l'optimisation minimale qui traite la cause principale.

Avant :
- résume la métrique ;
- identifie la cause probable ;
- définis le résultat attendu.

Après :
- reproduis la mesure ;
- compare avant/après ;
- vérifie les régressions ;
- évite les optimisations sans impact mesuré.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
