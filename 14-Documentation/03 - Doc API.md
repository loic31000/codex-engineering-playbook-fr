---
titre: "Documenter une API"
format: prompt
archetype: template
domaine: documentation
tags:
  - documentation
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
sortie_attendue: "documentation concise, actuelle et orientée usage"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : documentation concise, actuelle et orientée usage.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
