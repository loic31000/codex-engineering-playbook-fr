---
titre: "Architecture frontend"
format: prompt
archetype: workflow
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

# Architecture frontend

## Quand l'utiliser

Au début d'une app web ou lors d'une refonte structurelle.

## Prompt prêt à copier

```text
Agis comme un architecte frontend senior.

À partir du produit et des contraintes, propose l'architecture frontend.

Couvre :
- routing ;
- layout ;
- séparation server/client si applicable ;
- data fetching ;
- state local/global ;
- formulaires ;
- gestion erreurs ;
- auth côté UI ;
- composants partagés ;
- design system ;
- tests ;
- performance ;
- accessibilité ;
- observabilité frontend.

Privilégie la simplicité.
N'introduis pas de state global ou abstraction sans besoin clair.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
