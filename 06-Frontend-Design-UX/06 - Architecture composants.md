---
titre: "Architecture des composants"
format: prompt
archetype: instruction
domaine: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
sortie_attendue: "recommandation frontend/design directement exploitable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
