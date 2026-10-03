---
titre: "Évaluer la qualité d'un prompt"
format: prompt
archetype: checklist
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

# Évaluer la qualité d'un prompt

## Quand l'utiliser

Pour stabiliser ta bibliothèque.

## Prompt prêt à copier

```text
Évalue ce prompt sur 10 dimensions :

- objectif clair ;
- contexte suffisant ;
- scope ;
- contraintes ;
- sortie attendue ;
- testabilité ;
- absence d'ambiguïté ;
- absence de sur-guidage ;
- conditions d'escalade ;
- réutilisabilité.

Pour chaque dimension :
- problème ;
- impact ;
- correction.

Puis propose une version révisée.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
