---
titre: "Politique de dépendances"
format: prompt
archetype: instruction
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

# Politique de dépendances

## Quand l'utiliser

Pour éviter la prolifération de bibliothèques.

## Prompt prêt à copier

```text
Définis une politique simple pour les nouvelles dépendances.

Inclure :
- quand une dépendance externe est justifiée ;
- critères d'évaluation ;
- sécurité/supply chain ;
- maintenance ;
- taille/coût runtime ;
- licence ;
- lockfile ;
- alternatives natives ;
- procédure de revue ;
- règle de suppression des dépendances inutilisées.

La politique doit rester courte et applicable.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
