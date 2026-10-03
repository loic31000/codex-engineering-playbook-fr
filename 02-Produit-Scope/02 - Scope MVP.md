---
titre: "Définir le scope MVP"
format: prompt
archetype: instruction
domaine: produit
tags:
  - mvp
  - scope
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
sortie_attendue: "périmètre MVP défendable et limité"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Définir le scope MVP

## Quand l'utiliser

Quand tu dois éviter que le MVP grossisse en permanence.

## Prompt prêt à copier

```text
Aide-moi à définir le scope MVP.

Classe les capacités en :
- indispensable au problème principal ;
- utile mais reportable ;
- explicitement hors MVP ;
- inconnu / décision requise.

Pour chaque capacité indispensable :
- utilisateur concerné ;
- valeur produite ;
- dépendances ;
- risque ;
- critère permettant de dire qu'elle est suffisamment réalisée pour le MVP.

Ne propose pas de fonctionnalités supplémentaires sans les placer dans « futur possible ».

Sortie : périmètre MVP défendable et limité.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un périmètre MVP défendable et limité.

## Points de contrôle

- [ ] Hors scope présent
- [ ] Pas de feature creep
