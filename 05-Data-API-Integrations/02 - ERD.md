---
titre: "Préparer un ERD"
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
```

## Sortie attendue

Un design de données/API explicite et vérifiable.
