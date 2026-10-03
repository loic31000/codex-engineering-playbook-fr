---
titre: "Analyser les risques produit"
format: prompt
archetype: instruction
domaine: produit
tags:
  - risk
  - product
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
sortie_attendue: "registre de risques produit priorisable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Analyser les risques produit

## Quand l'utiliser

Avant un MVP ou une grosse feature.

## Prompt prêt à copier

```text
Analyse les risques produit de cette initiative.

Pour chaque risque :
- description ;
- catégorie ;
- probabilité qualitative ;
- impact ;
- signal d'alerte ;
- mitigation ;
- décision associée.

Cherche notamment :
- mauvais problème ;
- mauvais utilisateur ;
- scope trop large ;
- dépendance externe ;
- comportement critique non défini ;
- adoption ;
- contraintes légales ;
- dette UX.

Ne mélange pas risques techniques et faits établis.

Sortie : registre de risques produit priorisable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un registre de risques produit priorisable.

## Points de contrôle

- [ ] Risque ≠ certitude
- [ ] Mitigations concrètes
