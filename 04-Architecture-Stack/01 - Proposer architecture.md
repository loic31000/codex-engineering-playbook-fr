---
titre: "Proposer une architecture"
format: prompt
archetype: workflow
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Proposer une architecture

## Quand l'utiliser

Quand l'architecture n'est pas encore choisie.

## Prompt prêt à copier

```text
À partir des contraintes confirmées du projet, propose 2 à 4 architectures plausibles.

Pour chaque option :
- structure ;
- avantages ;
- inconvénients ;
- complexité opérationnelle ;
- impact tests ;
- impact sécurité ;
- impact évolutivité ;
- coût cognitif pour l'équipe ;
- risques.

Puis indique laquelle paraît la plus adaptée ET pourquoi, mais marque-la comme recommandation et non comme décision.

Privilégie la solution la plus simple qui satisfait réellement les contraintes.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
