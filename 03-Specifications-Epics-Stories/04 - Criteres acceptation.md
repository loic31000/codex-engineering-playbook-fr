---
titre: "Améliorer les critères d'acceptation"
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
sortie_attendue: "Des critères d'acceptation mesurables"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : Des critères d'acceptation mesurables.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Des critères d'acceptation mesurables.
