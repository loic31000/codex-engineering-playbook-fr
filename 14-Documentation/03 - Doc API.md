---
titre: "Documenter une API"
type: prompt
tags:
  - documentation
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Documenter une API

## Quand l'utiliser

Après design/implémentation.

## Prompt prêt à copier

```text
Rédige la documentation de cette API.

Pour chaque endpoint/opération :
- objectif ;
- auth ;
- input ;
- output ;
- erreurs ;
- exemples courts ;
- pagination/filtrage ;
- idempotence ;
- rate limiting ;
- versioning.

Ajoute les breaking changes et politiques de compatibilité.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
