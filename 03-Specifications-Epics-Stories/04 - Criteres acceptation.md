---
titre: "Améliorer les critères d'acceptation"
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

# Améliorer les critères d'acceptation

## Quand l'utiliser

Quand les critères sont trop vagues ou ressemblent à des tâches techniques.

## Prompt prêt à copier

```text
Revois les critères d'acceptation de cette Story.

Pour chaque critère :
- vérifie qu'il décrit un comportement/résultat observable ;
- vérifie qu'il est testable ;
- supprime les doublons ;
- identifie les critères manquants ;
- ajoute les erreurs/permissions/edge cases réellement nécessaires.

Utilise Given/When/Then lorsque cela améliore la précision, sans l'imposer artificiellement.

Ne change pas le scope métier.
```

## Sortie attendue

Des critères d'acceptation mesurables.
