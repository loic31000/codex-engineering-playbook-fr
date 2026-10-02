---
titre: "Refactor contrôlé"
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
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
