---
titre: "Découper un plan en tâches"
format: prompt
archetype: workflow
domaine: planification
tags:
  - planning
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
sortie_attendue: "plan/tâches actionnables"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Découper un plan en tâches

## Quand l'utiliser

Après validation du plan.

## Prompt prêt à copier

```text
Découpe ce plan en tâches petites et ordonnées.

Chaque tâche doit :
- avoir un objectif unique ;
- produire un résultat vérifiable ;
- indiquer dépendances ;
- préciser fichiers/composants probables ;
- inclure tests ;
- rester suffisamment petite pour une revue claire.

Évite les tâches vagues comme « faire le frontend ».

Sortie : plan/tâches actionnables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un plan/tâches actionnables.
