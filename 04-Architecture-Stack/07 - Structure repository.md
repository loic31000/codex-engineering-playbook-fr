---
titre: "Définir la structure du repository"
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

# Définir la structure du repository

## Quand l'utiliser

Quand le codebase a besoin d'une organisation claire.

## Prompt prêt à copier

```text
Propose une structure de repository adaptée à l'architecture validée.

Pour chaque dossier principal :
- responsabilité ;
- ce qui peut y entrer ;
- ce qui ne doit pas y entrer ;
- dépendances permises.

Favorise :
- découvrabilité ;
- proximité code/tests ;
- frontières visibles ;
- conventions simples.

Évite les arborescences profondes sans valeur.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
