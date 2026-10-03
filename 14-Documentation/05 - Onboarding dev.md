---
titre: "Créer guide onboarding"
format: prompt
archetype: template
domaine: documentation
tags:
  - documentation
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
sortie_attendue: "documentation concise, actuelle et orientée usage"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Créer guide onboarding

## Quand l'utiliser

Pour nouveaux développeurs.

## Prompt prêt à copier

```text
Crée un parcours d'onboarding développeur.

Ordre :
- comprendre produit ;
- lancer localement ;
- tests ;
- architecture ;
- conventions ;
- première petite tâche ;
- CI ;
- déploiement ;
- sécurité ;
- où poser questions.

Vise une première contribution rapide sans masquer les règles importantes.

Sortie : documentation concise, actuelle et orientée usage.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
