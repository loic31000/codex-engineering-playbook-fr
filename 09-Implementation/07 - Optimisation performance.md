---
titre: "Optimiser après mesure"
type: prompt
tags:
  - implementation
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
