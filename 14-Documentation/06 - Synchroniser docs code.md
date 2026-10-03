---
titre: "Synchroniser documentation et code"
format: prompt
archetype: workflow
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

# Synchroniser documentation et code

## Quand l'utiliser

Après une grosse PR.

## Prompt prêt à copier

```text
Compare la documentation durable avec le code actuel.

Identifie :
- docs obsolètes ;
- comportements non documentés ;
- architecture drift ;
- commandes cassées ;
- config manquante ;
- endpoints modifiés ;
- décisions non tracées.

Propose uniquement les mises à jour nécessaires.

Sortie : documentation concise, actuelle et orientée usage.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
