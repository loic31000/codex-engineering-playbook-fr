---
titre: "Concevoir thèmes et dark mode"
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

# Concevoir thèmes et dark mode

## Quand l'utiliser

Quand le produit nécessite plusieurs thèmes.

## Prompt prêt à copier

```text
Conçois un système de thèmes robuste.

Définis des tokens sémantiques plutôt que des couleurs codées par composant.

Couvre :
- background/surface ;
- texte ;
- borders ;
- brand ;
- interactive ;
- success/warning/error ;
- focus ;
- overlays ;
- graphiques ;
- syntaxe si applicable.

Vérifie :
- contrastes ;
- images/logos ;
- ombres ;
- élévation ;
- préférence système ;
- changement de thème ;
- flash au chargement.

Ne fais pas un simple inversement de couleurs.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
