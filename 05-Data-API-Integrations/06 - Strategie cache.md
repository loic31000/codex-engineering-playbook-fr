---
titre: "Concevoir une stratégie de cache"
format: prompt
archetype: instruction
domaine: data-api
tags:
  - data
  - api
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
sortie_attendue: "design de données/API explicite et vérifiable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : design de données/API explicite et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
