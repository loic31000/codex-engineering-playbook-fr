---
titre: "Créer une Epic"
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
sortie_attendue: "Epic cohérente et découpable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Créer une Epic

## Quand l'utiliser

Quand une initiative dépasse une seule Story.

## Prompt prêt à copier

```text
Transforme ce besoin en Epic structurée.

Inclure :
- objectif métier ;
- résultat attendu ;
- utilisateurs concernés ;
- scope ;
- hors scope ;
- critères de succès ;
- dépendances ;
- risques ;
- impact architecture/data/sécurité/UX ;
- Stories candidates.

Ne détaille pas encore l'implémentation technique.
Chaque Story candidate doit représenter une valeur ou un résultat vérifiable.

Sortie : Epic cohérente et découpable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une Epic cohérente et découpable.
