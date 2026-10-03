---
titre: "Implémenter un changement API"
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

# Implémenter un changement API

## Quand l'utiliser

Pour modifier un contrat existant.

## Prompt prêt à copier

```text
Implémente ce changement API en protégeant les consommateurs existants.

Vérifie :
- contrat actuel ;
- breaking change ;
- versioning ;
- validation ;
- erreurs ;
- auth ;
- observabilité ;
- documentation ;
- tests contractuels ;
- migration consommateurs.

Si le changement est breaking, ne le cache pas derrière une implémentation silencieuse.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
