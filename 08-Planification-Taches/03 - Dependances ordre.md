---
titre: "Analyser dépendances et ordre"
format: prompt
archetype: instruction
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

# Analyser dépendances et ordre

## Quand l'utiliser

Quand plusieurs tâches peuvent se bloquer.

## Prompt prêt à copier

```text
Construis le graphe de dépendances de ces tâches.

Pour chaque tâche :
- dépend de ;
- bloque ;
- peut être parallèle ;
- risque ;
- preuve de completion.

Propose un ordre qui maximise :
- feedback rapide ;
- réduction du risque ;
- travail parallèle ;
- disponibilité des fondations.

Sortie : plan/tâches actionnables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un plan/tâches actionnables.
