---
titre: "Concevoir les E2E critiques"
type: prompt
tags:
  - testing
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Concevoir les E2E critiques

## Quand l'utiliser

Pour parcours utilisateur essentiels.

## Prompt prêt à copier

```text
À partir des critères d'acceptation, sélectionne les parcours qui méritent un E2E.

Pour chaque scénario :
- préconditions ;
- étapes utilisateur ;
- résultat visible ;
- assertions ;
- données ;
- cleanup ;
- erreurs ;
- navigateur/device si pertinent.

Évite de dupliquer toute la suite unitaire en E2E.
```

## Sortie attendue

Une stratégie ou suite de tests alignée sur les risques.
