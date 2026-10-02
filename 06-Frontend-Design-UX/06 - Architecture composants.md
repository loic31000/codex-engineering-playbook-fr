---
titre: "Architecture des composants"
type: prompt
tags:
  - frontend
  - design
  - ux
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Architecture des composants

## Quand l'utiliser

Avant de découper un écran en composants React/Vue/etc.

## Prompt prêt à copier

```text
Propose une architecture de composants pour cet écran/feature.

Pour chaque composant :
- responsabilité ;
- données reçues ;
- événements émis ;
- état local ;
- dépendances ;
- réutilisabilité réelle ;
- test nécessaire.

Distingue :
- primitives design system ;
- composants de domaine ;
- composants de page ;
- logique métier.

Évite les composants trop génériques et les props booléennes qui explosent en combinaisons.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
