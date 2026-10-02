---
titre: "Implémenter une migration DB"
type: prompt
tags:
  - implementation
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
