---
titre: "Implémenter avec feature flag"
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

# Implémenter avec feature flag

## Quand l'utiliser

Pour réduire le risque de rollout.

## Prompt prêt à copier

```text
Planifie et implémente cette feature derrière un feature flag.

Définis :
- flag ;
- valeur par défaut ;
- population ;
- comportement off ;
- comportement on ;
- migration données éventuelle ;
- analytics/observabilité ;
- rollback ;
- date/condition de suppression du flag.

Évite les flags permanents sans propriétaire.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
