---
titre: "Concevoir le modèle de données"
format: prompt
archetype: template
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

Sortie : design de données/API explicite et vérifiable.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
