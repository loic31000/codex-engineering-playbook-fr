---
titre: "Documenter modèle de données"
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

# Documenter modèle de données

## Quand l'utiliser

Pour comprendre ownership et contraintes.

## Prompt prêt à copier

```text
Rédige une documentation du modèle de données orientée ingénierie.

Inclure :
- entités ;
- ownership ;
- relations ;
- invariants ;
- sensibilité ;
- rétention ;
- migrations ;
- tenant isolation ;
- indexes/contraintes importants.

Évite une simple copie du schema SQL.

Sortie : documentation concise, actuelle et orientée usage.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
