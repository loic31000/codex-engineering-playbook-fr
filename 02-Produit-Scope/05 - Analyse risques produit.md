---
titre: "Analyser les risques produit"
type: prompt
tags:
  - risk
  - product
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un registre de risques produit priorisable.

## Points de contrôle

- [ ] Risque ≠ certitude
- [ ] Mitigations concrètes
