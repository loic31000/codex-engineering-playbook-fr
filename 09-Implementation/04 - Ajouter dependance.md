---
titre: "Évaluer puis ajouter une dépendance"
type: prompt
tags:
  - implementation
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
