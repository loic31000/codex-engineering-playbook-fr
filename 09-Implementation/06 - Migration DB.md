---
titre: "Implémenter une migration DB"
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

# Implémenter une migration DB

## Quand l'utiliser

Après validation du plan de migration.

## Prompt prêt à copier

```text
Implémente cette migration de manière sûre.

Respecte le plan validé.

Vérifie :
- forward compatibility ;
- backfill ;
- contraintes ;
- index ;
- locks potentiels ;
- ordre déploiement code/schema ;
- rollback ou forward fix ;
- données existantes ;
- tests.

Ne fais pas de suppression destructive prématurée.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
