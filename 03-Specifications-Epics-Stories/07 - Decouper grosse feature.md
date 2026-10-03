---
titre: "Découper une grosse feature"
format: prompt
archetype: workflow
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
sortie_attendue: "découpage implémentable de la feature"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Découper une grosse feature

## Quand l'utiliser

Quand une Story ou feature est trop grosse.

## Prompt prêt à copier

```text
Découpe cette feature en incréments petits, cohérents et vérifiables.

Contraintes :
- chaque Story doit avoir une valeur ou un résultat observable ;
- minimiser les dépendances circulaires ;
- permettre des PR raisonnables ;
- éviter les Stories uniquement « backend » puis « frontend » sauf nécessité technique réelle ;
- identifier les fondations techniques si elles doivent précéder la valeur utilisateur ;
- conserver la traçabilité vers la feature d'origine.

Pour chaque Story :
- objectif ;
- AC principaux ;
- dépendances ;
- ordre recommandé ;
- risque.

Sortie : découpage implémentable de la feature.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un découpage implémentable de la feature.
