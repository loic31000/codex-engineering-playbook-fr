---
titre: "Convergence spec/code/tests"
format: prompt
archetype: checklist
domaine: review-convergence
tags:
  - review
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
sortie_attendue: "review priorisée et actionnable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : review priorisée et actionnable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une review priorisée et actionnable.
