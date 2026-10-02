---
titre: "Planifier une migration de base"
type: prompt
tags:
  - data
  - api
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Planifier une migration de base

## Quand l'utiliser

Avant une modification de schéma risquée.

## Prompt prêt à copier

```text
Prépare un plan de migration de données sûr.

Inclure :
- état actuel ;
- état cible ;
- migration de schéma ;
- migration de données ;
- compatibilité pendant déploiement ;
- ordre des étapes ;
- backfill ;
- contraintes/index ;
- rollback ou stratégie forward-only ;
- impact disponibilité ;
- vérifications avant/après ;
- tests.

Évite les migrations destructrices en une seule étape si le système est en production.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
