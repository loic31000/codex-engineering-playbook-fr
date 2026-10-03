---
titre: "Préparer un spike technique"
format: prompt
archetype: instruction
domaine: planification
tags:
  - planning
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
sortie_attendue: "plan/tâches actionnables"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Préparer un spike technique

## Quand l'utiliser

Quand une inconnue bloque une décision.

## Prompt prêt à copier

```text
Transforme cette inconnue en spike technique limité.

Définis :
- question exacte ;
- hypothèses ;
- ce qu'il faut expérimenter ;
- ce qu'il ne faut pas construire ;
- durée/effort borné ;
- critères de décision ;
- artefact final attendu.

Le spike doit réduire l'incertitude, pas devenir une implémentation cachée.

Sortie : plan/tâches actionnables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un plan/tâches actionnables.
