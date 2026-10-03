---
titre: "Implémentation incrémentale"
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

# Implémentation incrémentale

## Quand l'utiliser

Pour réduire le risque sur une grosse modification.

## Prompt prêt à copier

```text
Implémente ce changement en incréments sûrs.

Avant chaque incrément :
- objectif précis ;
- comportement préservé ;
- test prévu.

Après chaque incrément :
- exécute les tests pertinents ;
- résume le résultat ;
- vérifie que le prochain incrément est toujours valide.

Ne regroupe pas plusieurs changements indépendants dans un même incrément.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
