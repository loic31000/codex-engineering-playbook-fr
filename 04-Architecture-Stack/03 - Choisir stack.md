---
titre: "Choisir une stack"
format: prompt
archetype: instruction
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Choisir une stack

## Quand l'utiliser

Quand plusieurs technologies sont possibles.

## Prompt prêt à copier

```text
Compare les options de stack uniquement à partir des besoins du projet.

Critères :
- adéquation au produit ;
- expertise disponible ;
- écosystème ;
- sécurité ;
- testabilité ;
- maturité ;
- maintenabilité ;
- performance nécessaire ;
- déploiement ;
- longévité ;
- lock-in.

Distingue :
- contraintes ;
- préférences ;
- choix recommandés ;
- décisions encore ouvertes.

Évite les choix motivés uniquement par la mode.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
