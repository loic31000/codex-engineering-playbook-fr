---
titre: "Définir modules et frontières"
format: prompt
archetype: instruction
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Définir modules et frontières

## Quand l'utiliser

Quand il faut structurer un monolithe ou des services.

## Prompt prêt à copier

```text
Propose des frontières de modules à partir des informations de domaine fournies.

Utilise :
- cas d'usage ;
- règles et invariants métier ;
- ownership des données ;
- dépendances existantes ;
- contraintes déjà confirmées.

Pour chaque module proposé :
- responsabilité ;
- données possédées ;
- contrats exposés ;
- dépendances autorisées et interdites ;
- événements éventuels ;
- invariants ;
- raisons de la frontière.

Puis liste :
- couplages problématiques ;
- décisions encore incertaines ;
- alternatives crédibles et leurs compromis.

Privilégie les frontières métier à un découpage par couches techniques.
Ne crée pas un bounded context uniquement pour obtenir une architecture symétrique.
N'invente pas de règles métier absentes du contexte.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
