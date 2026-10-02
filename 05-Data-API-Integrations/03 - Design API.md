---
titre: "Concevoir une API"
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

# Concevoir une API

## Quand l'utiliser

Avant d'implémenter une API nouvelle ou modifiée.

## Prompt prêt à copier

```text
Conçois le contrat API de cette fonctionnalité.

Précise :
- ressources/opérations ;
- entrées ;
- sorties ;
- validation ;
- auth/permissions ;
- codes d'erreur ;
- pagination/filtrage si applicable ;
- idempotence ;
- versioning ;
- rate limiting si nécessaire ;
- erreurs ;
- observabilité.

Sépare le contrat public des détails internes.
Signale tout breaking change.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
