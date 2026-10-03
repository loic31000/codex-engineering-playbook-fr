---
titre: "Concevoir loading, empty, error et succès"
format: prompt
archetype: instruction
domaine: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
sortie_attendue: "recommandation frontend/design directement exploitable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Concevoir loading, empty, error et succès

## Quand l'utiliser

Quand un écran n'est défini que pour le happy path.

## Prompt prêt à copier

```text
Pour cette interface, spécifie tous les états importants :

- chargement initial ;
- chargement partiel ;
- skeleton si pertinent ;
- empty state premier usage ;
- empty state après filtre ;
- erreur réseau ;
- erreur permission ;
- erreur validation ;
- données périmées ;
- retry ;
- succès ;
- traitement long ;
- offline si pertinent.

Pour chacun :
- message ;
- action possible ;
- ton ;
- composant ;
- accessibilité ;
- conservation du contexte utilisateur.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
