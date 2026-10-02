---
titre: "Concevoir le modèle de données"
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

# Concevoir le modèle de données

## Quand l'utiliser

Quand les entités et relations doivent être formalisées.

## Prompt prêt à copier

```text
À partir des règles métier confirmées, propose un modèle de données conceptuel.

Pour chaque entité :
- responsabilité ;
- identifiant ;
- attributs essentiels ;
- relations ;
- cardinalités ;
- invariants ;
- ownership ;
- cycle de vie ;
- contraintes d'unicité ;
- sensibilité des données.

Ne choisis pas encore des détails de stockage inutiles.
Signale les ambiguïtés métier.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
