---
titre: "Moderniser du legacy"
type: prompt
tags:
  - debug
  - maintenance
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
