---
titre: "Concevoir une stratégie de cache"
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

# Concevoir une stratégie de cache

## Quand l'utiliser

Quand la performance ou le coût justifie un cache.

## Prompt prêt à copier

```text
Avant de proposer un cache, vérifie qu'il répond à un problème mesuré ou plausible.

Définis :
- données cachées ;
- clé ;
- TTL ;
- invalidation ;
- cohérence ;
- stampede ;
- données sensibles ;
- multi-tenancy ;
- fallback ;
- observabilité ;
- risque de stale data.

Explique aussi quand NE PAS mettre de cache.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
