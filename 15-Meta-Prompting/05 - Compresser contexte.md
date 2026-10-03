---
titre: "Compresser un contexte projet"
format: prompt
archetype: workflow
domaine: meta-prompting
tags:
  - prompting
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
sortie_attendue: "prompt ou workflow plus robuste"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Compresser un contexte projet

## Quand l'utiliser

Quand la conversation devient trop longue.

## Prompt prêt à copier

```text
Transforme ce contexte en briefing compact pour une nouvelle session Codex.

Conserve uniquement :
- objectif ;
- état actuel ;
- décisions confirmées ;
- hypothèses ;
- architecture pertinente ;
- fichiers pertinents ;
- contraintes ;
- tests ;
- problèmes ouverts ;
- prochaine action.

Supprime :
- discussions historiques ;
- alternatives rejetées sans conséquence ;
- répétitions ;
- détails inutiles.

Sortie : prompt ou workflow plus robuste.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
