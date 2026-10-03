---
titre: "Créer un ExecPlan"
format: prompt
archetype: template
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

# Créer un ExecPlan

## Quand l'utiliser

Pour une Story complexe, migration ou refactor important.

## Prompt prêt à copier

```text
Crée un plan d'exécution détaillé sans écrire le code.

Inclure :
- objectif ;
- contexte ;
- préconditions ;
- fichiers/composants affectés ;
- séquence d'implémentation ;
- migrations ;
- API ;
- sécurité ;
- tests ;
- rollout ;
- rollback ;
- risques ;
- points de vérification.

Le plan doit être exécutable par un autre développeur sans avoir besoin de cette conversation.

Sortie : plan/tâches actionnables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un plan/tâches actionnables.
