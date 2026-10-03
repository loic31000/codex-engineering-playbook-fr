---
titre: "Concevoir une API"
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

Sortie : design de données/API explicite et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
