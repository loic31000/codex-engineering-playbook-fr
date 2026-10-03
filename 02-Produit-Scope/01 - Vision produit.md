---
titre: "Formaliser la vision produit"
format: prompt
archetype: instruction
domaine: produit
tags:
  - product
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
sortie_attendue: "vision produit utilisable pour la suite de la spécification"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Formaliser la vision produit

## Quand l'utiliser

Quand l'idée existe mais n'est pas encore formulée proprement.

## Prompt prêt à copier

```text
À partir des informations disponibles, rédige une vision produit concise.

Structure :
- problème ;
- utilisateurs cibles ;
- contexte ;
- résultat attendu ;
- proposition de valeur ;
- indicateurs de succès ;
- non-objectifs ;
- hypothèses produit ;
- questions ouvertes.

N'invente pas de métriques si elles ne sont pas connues.
Transforme les formulations vagues en questions lorsque nécessaire.

Sortie : vision produit utilisable pour la suite de la spécification.
```

## Sortie attendue

Une vision produit utilisable pour la suite de la spécification.

## Points de contrôle

- [ ] Problème distinct de la solution
- [ ] Non-objectifs explicites
