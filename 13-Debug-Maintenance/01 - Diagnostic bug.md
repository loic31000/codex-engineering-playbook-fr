---
titre: "Diagnostiquer un bug"
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

# Diagnostiquer un bug

## Quand l'utiliser

Quand le symptôme est connu mais pas la cause.

## Prompt prêt à copier

```text
Diagnostique ce bug avant de proposer un correctif.

Procédure :
1. reformule le symptôme ;
2. précise expected vs actual ;
3. identifie conditions de reproduction ;
4. localise les frontières impliquées ;
5. formule plusieurs hypothèses ;
6. cherche les preuves qui confirment/infirment chaque hypothèse ;
7. trouve la cause racine la plus probable ;
8. propose le test de régression ;
9. seulement ensuite propose le correctif minimal.

Ne change pas plusieurs choses à la fois.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
