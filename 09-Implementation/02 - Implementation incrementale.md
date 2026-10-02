---
titre: "Implémentation incrémentale"
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
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
