---
titre: "Découper une grosse feature"
type: prompt
tags:
  - spec
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un découpage implémentable de la feature.
