---
titre: "Moderniser du legacy"
format: prompt
archetype: workflow
domaine: debug-maintenance
tags:
  - debug
  - maintenance
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
sortie_attendue: "diagnostic ou plan de maintenance fondé sur des preuves"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Moderniser du legacy

## Quand l'utiliser

Quand il faut améliorer sans réécrire tout.

## Prompt prêt à copier

```text
Propose une stratégie de modernisation incrémentale.

D'abord :
- comportement critique à préserver ;
- zones stables ;
- zones douloureuses ;
- tests existants ;
- frontières possibles.

Puis :
- strangler/incréments ;
- points de découpe ;
- tests de caractérisation ;
- migrations ;
- critères de sortie.

Évite la réécriture totale par défaut.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
