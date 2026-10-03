---
titre: "Review visuelle finale"
format: prompt
archetype: checklist
domaine: review-convergence
tags:
  - review
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
sortie_attendue: "review priorisée et actionnable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Review visuelle finale

## Quand l'utiliser

Avant merge d'un écran frontend.

## Prompt prêt à copier

```text
Revois l'interface finale comme un design QA.

Vérifie :
- cohérence design system ;
- spacing ;
- alignements ;
- typo ;
- couleurs ;
- contrastes ;
- responsive ;
- états ;
- interactions ;
- clavier/focus ;
- erreurs ;
- loading/empty ;
- densité ;
- mobile ;
- polish.

Sépare bloquants UX/accessibilité des détails purement esthétiques.

Sortie : review priorisée et actionnable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une review priorisée et actionnable.
