---
titre: "Diagnostiquer performance"
format: prompt
archetype: workflow
domaine: debug-maintenance
tags:
  - debug
  - maintenance
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
sortie_attendue: "diagnostic ou plan de maintenance fondé sur des preuves"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
