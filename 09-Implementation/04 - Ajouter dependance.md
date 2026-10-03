---
titre: "Évaluer puis ajouter une dépendance"
format: prompt
archetype: workflow
domaine: implementation
tags:
  - implementation
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
sortie_attendue: "implémentation contrôlée, testée et dans le scope"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Évaluer puis ajouter une dépendance

## Quand l'utiliser

Avant npm install/pip install/etc.

## Prompt prêt à copier

```text
Avant d'ajouter cette dépendance, évalue si elle est réellement nécessaire.

Compare :
- solution native ;
- petite implémentation locale ;
- dépendance proposée ;
- alternatives.

Évalue :
- maintenance ;
- maturité ;
- sécurité ;
- taille ;
- transitive dependencies ;
- licence ;
- API ;
- lock-in.

Si la dépendance est retenue, explique :
- pourquoi ;
- version ;
- zone d'usage ;
- plan de test.

Sortie : implémentation contrôlée, testée et dans le scope.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
