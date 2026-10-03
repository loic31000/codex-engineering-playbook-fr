---
titre: "Extraire les décisions d'une conversation"
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

# Extraire les décisions d'une conversation

## Quand l'utiliser

Après une longue session.

## Prompt prêt à copier

```text
À partir de cette conversation, extrais uniquement les décisions durables.

Pour chacune :
- décision ;
- état : confirmé/hypothèse/indécis ;
- justification ;
- conséquence ;
- document à mettre à jour ;
- besoin éventuel d'ADR.

Ne transforme pas une suggestion en décision confirmée.

Sortie : prompt ou workflow plus robuste.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
