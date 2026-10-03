---
titre: "Plan de tests accessibilité"
format: prompt
archetype: checklist
domaine: tests-qualite
tags:
  - testing
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
sortie_attendue: "stratégie ou suite de tests alignée sur les risques"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Plan de tests accessibilité

## Quand l'utiliser

Pour une feature UI.

## Prompt prêt à copier

```text
Définis les tests accessibilité de cette interface.

Inclure :
- automatisé ;
- navigation clavier ;
- focus ;
- screen reader ciblé ;
- contrastes ;
- zoom/reflow ;
- reduced motion ;
- formulaires ;
- erreurs ;
- dialogs ;
- mobile/touch.

Distingue ce qui peut être automatisé de ce qui nécessite vérification manuelle.

Sortie : stratégie ou suite de tests alignée sur les risques.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
