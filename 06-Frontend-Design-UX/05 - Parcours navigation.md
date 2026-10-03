---
titre: "Concevoir navigation et parcours"
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

# Concevoir navigation et parcours

## Quand l'utiliser

Quand l'information ou les parcours sont confus.

## Prompt prêt à copier

```text
Analyse les tâches principales des utilisateurs et propose une architecture de navigation.

Définis :
- navigation primaire ;
- navigation secondaire ;
- breadcrumb si utile ;
- profondeur ;
- routes ;
- points d'entrée ;
- sorties ;
- retours arrière ;
- états persistants ;
- contexte tenant/projet ;
- navigation mobile.

Pour chaque parcours critique, donne :
- déclencheur ;
- étapes minimales ;
- décisions utilisateur ;
- erreurs possibles ;
- succès.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
