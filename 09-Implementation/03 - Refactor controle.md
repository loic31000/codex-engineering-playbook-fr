---
titre: "Refactor contrôlé"
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

# Refactor contrôlé

## Quand l'utiliser

Quand tu veux améliorer la structure sans changer le comportement.

## Prompt prêt à copier

```text
Refactore ce code sans modifier le comportement observable.

Avant :
- décris le comportement à préserver ;
- identifie les tests de protection ;
- identifie les risques.

Pendant :
- fais des étapes petites ;
- ne mélange pas feature et refactor ;
- supprime les abstractions inutiles ;
- réduis duplication/couplage si cela reste lisible.

Après :
- compare comportement/tests ;
- liste les changements structurels ;
- signale toute différence volontaire.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
