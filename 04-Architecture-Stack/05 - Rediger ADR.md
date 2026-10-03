---
titre: "Rédiger un ADR"
format: prompt
archetype: template
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Rédiger un ADR

## Quand l'utiliser

Quand une décision technique importante doit être traçable.

## Prompt prêt à copier

```text
Rédige un ADR pour cette décision.

Structure :
- titre ;
- statut ;
- contexte ;
- forces/contraintes ;
- options considérées ;
- décision ;
- justification ;
- conséquences positives ;
- conséquences négatives/trade-offs ;
- impact sécurité/data ;
- migration éventuelle ;
- vérification ;
- critères de réévaluation.

Reste factuel. Ne présente pas une préférence comme une contrainte.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
