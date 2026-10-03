---
titre: "Créer une User Story"
format: prompt
archetype: template
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
sortie_attendue: "Story testable et prête à clarifier"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Créer une User Story

## Quand l'utiliser

Quand un besoin doit devenir une unité de travail.

## Prompt prêt à copier

```text
Transforme le besoin fourni en une User Story focalisée et testable.

Sortie :
- titre ;
- utilisateur ou acteur concerné ;
- besoin ou objectif ;
- valeur recherchée ;
- scope ;
- hors scope ;
- critères d'acceptation observables ;
- edge cases importants ;
- dépendances connues ;
- impacts sécurité / data / UI / API ;
- méthode de vérification.

N'ajoute aucun coût financier.
N'ajoute pas de détail d'implémentation qui n'est pas déjà contraint.

Si le besoin contient plusieurs résultats indépendants, ne fabrique pas une Story géante : propose un découpage en Stories verticales et explique brièvement la frontière.

Marque toute information inconnue comme « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une Story testable et prête à clarifier.
