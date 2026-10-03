---
titre: "Diagnostiquer un bug"
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

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
