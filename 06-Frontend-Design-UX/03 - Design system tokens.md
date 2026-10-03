---
titre: "Définir un design system et ses tokens"
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

# Définir un design system et ses tokens

## Quand l'utiliser

Avant de construire beaucoup de composants.

## Prompt prêt à copier

```text
Conçois un design system minimal mais extensible.

Définis les tokens :
- couleurs sémantiques ;
- typographie ;
- spacing ;
- tailles ;
- radius ;
- borders ;
- shadows ;
- z-index ;
- breakpoints ;
- motion ;
- focus ;
- états disabled/error/success/warning.

Puis définis :
- primitives ;
- composants de base ;
- règles de composition ;
- thèmes éventuels.

Évite un design system gigantesque avant les besoins réels.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
