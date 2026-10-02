---
titre: "Plan de rollback"
type: prompt
tags:
  - git
  - release
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Plan de rollback

## Quand l'utiliser

Pour une release risquée.

## Prompt prêt à copier

```text
Prépare le rollback de cette release.

Définis :
- signal déclencheur ;
- décisionnaire ;
- étapes ;
- code ;
- DB ;
- cache ;
- queues ;
- feature flags ;
- data forward-only éventuelle ;
- validation après rollback ;
- communication ;
- risques du rollback lui-même.
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
