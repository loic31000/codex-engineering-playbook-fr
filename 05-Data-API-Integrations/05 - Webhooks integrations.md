---
titre: "Concevoir webhooks et intégrations"
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

# Concevoir webhooks et intégrations

## Quand l'utiliser

Pour intégrer des systèmes externes de façon robuste.

## Prompt prêt à copier

```text
Analyse cette intégration externe.

Définis :
- contrat entrant/sortant ;
- authentification/signature ;
- idempotence ;
- retry ;
- timeout ;
- ordre des événements ;
- replay ;
- déduplication ;
- rate limits ;
- erreurs ;
- stockage minimal nécessaire ;
- observabilité ;
- secret management ;
- mode dégradé.

Liste les hypothèses dépendantes du fournisseur.

Sortie : design de données/API explicite et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
