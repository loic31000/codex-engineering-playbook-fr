---
titre: "Estimer la complexité"
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

# Estimer la complexité

## Quand l'utiliser

Pour planifier sans mettre des coûts financiers dans les Stories.

## Prompt prêt à copier

```text
Estime uniquement la complexité et l'effort relatif de ces tâches.

Utilise :
- small ;
- medium ;
- large ;
- complex.

Justifie selon :
- inconnues ;
- surface de code ;
- dépendances ;
- migration ;
- sécurité ;
- tests ;
- intégrations ;
- frontend ;
- risque.

N'inclus aucun prix ni coût financier.

Sortie : plan/tâches actionnables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un plan/tâches actionnables.
