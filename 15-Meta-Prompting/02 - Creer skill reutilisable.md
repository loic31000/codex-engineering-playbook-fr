---
titre: "Créer un skill réutilisable"
format: prompt
archetype: workflow
domaine: meta-prompting
tags:
  - prompting
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
sortie_attendue: "prompt ou workflow plus robuste"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Créer un skill réutilisable

## Quand l'utiliser

Quand un workflow revient souvent.

## Prompt prêt à copier

```text
Transforme ce workflow en skill Markdown réutilisable.

Structure :
- nom ;
- description déclencheuse ;
- objectif ;
- quand l'utiliser ;
- contexte requis ;
- préconditions ;
- procédure ;
- contraintes ;
- sortie ;
- vérification ;
- conditions d'arrêt/escalade.

Le skill doit être focalisé sur un workflow unique.
Évite d'y mettre toute la documentation projet.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
