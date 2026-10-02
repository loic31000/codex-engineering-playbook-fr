---
titre: "Convergence spec/code/tests"
type: prompt
tags:
  - review
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Convergence spec/code/tests

## Quand l'utiliser

Après implémentation, avant PR.

## Prompt prêt à copier

```text
Vérifie la convergence entre :
- Story/spec ;
- plan ;
- code ;
- tests ;
- documentation.

Construis une matrice :
- exigence ;
- implémentation ;
- test ;
- doc ;
- statut.

Identifie :
- exigence oubliée ;
- code hors scope ;
- test manquant ;
- documentation obsolète ;
- décision technique non documentée.

Ne modifie pas la spec uniquement pour justifier le code.
```

## Sortie attendue

Une review priorisée et actionnable.
