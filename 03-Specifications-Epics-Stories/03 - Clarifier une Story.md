---
titre: "Clarifier une Story"
type: prompt
tags:
  - spec
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une Story dont les ambiguïtés importantes sont explicitement traitées.
