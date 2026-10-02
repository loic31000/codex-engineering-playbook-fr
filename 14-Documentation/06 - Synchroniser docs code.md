---
titre: "Synchroniser documentation et code"
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
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
