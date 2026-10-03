---
titre: "Préparer un ERD"
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

# Préparer un ERD

## Quand l'utiliser

Quand tu veux formaliser les relations avant migration.

## Prompt prêt à copier

```text
Transforme ce modèle métier en description d'ERD.

Inclure :
- entités ;
- PK ;
- FK ;
- relations ;
- cardinalités ;
- contraintes importantes ;
- tables d'association ;
- ownership tenant si applicable.

Ajoute une section :
- risques d'intégrité ;
- décisions de normalisation ;
- index potentiels à mesurer ;
- points à clarifier.

Sortie : design de données/API explicite et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
