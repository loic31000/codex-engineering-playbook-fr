---
titre: "Review frontend finale"
format: prompt
archetype: checklist
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

# Review frontend finale

## Quand l'utiliser

Avant merge d'une feature frontend.

## Prompt prêt à copier

```text
Fais une review frontend complète de ce diff.

Évalue :
- respect de la Story ;
- architecture composants ;
- state management ;
- data fetching ;
- erreurs ;
- responsive ;
- accessibilité ;
- design system ;
- performance ;
- sécurité frontend ;
- tests ;
- duplication ;
- dead code ;
- cohérence UX.

Sépare :
- bloquants ;
- recommandations ;
- polish optionnel.

Ne demande pas un refactor sans impact concret.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
