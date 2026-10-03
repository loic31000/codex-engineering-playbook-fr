---
titre: "Clarifier une Story"
format: prompt
archetype: instruction
domaine: specifications
tags:
  - spec
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
sortie_attendue: "Story dont les ambiguïtés importantes sont explicitement traitées"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Clarifier une Story

## Quand l'utiliser

Quand la Story paraît vague ou contient des mots comme rapide, intuitif, sécurisé, etc.

## Prompt prêt à copier

```text
Analyse cette Story et ne l'implémente pas.

Trouve :
- ambiguïtés ;
- termes subjectifs ;
- décisions manquantes ;
- comportements contradictoires ;
- edge cases ;
- dépendances cachées ;
- exigences sécurité/data non explicitées ;
- critères d'acceptation non testables.

Pose ensuite uniquement les questions qui peuvent modifier le comportement attendu, l'architecture, la sécurité ou le scope.

Après clarification, propose une version révisée sans inventer de réponse.

Sortie : Story dont les ambiguïtés importantes sont explicitement traitées.
```

## Sortie attendue

Une Story dont les ambiguïtés importantes sont explicitement traitées.
