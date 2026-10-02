---
titre: "Concevoir webhooks et intégrations"
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
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
