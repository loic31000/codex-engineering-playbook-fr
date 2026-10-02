---
titre: "Diagnostiquer performance"
type: prompt
tags:
  - debug
  - maintenance
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Diagnostiquer performance

## Quand l'utiliser

Avant toute optimisation.

## Prompt prêt à copier

```text
À partir des symptômes et mesures, construis un plan de profiling.

Sépare :
- CPU ;
- mémoire ;
- I/O ;
- DB ;
- réseau ;
- frontend ;
- dépendances externes.

Définis pour chaque hypothèse :
- métrique ;
- outil/observation ;
- seuil de comparaison ;
- expérience.

N'optimise pas avant identification du bottleneck.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
