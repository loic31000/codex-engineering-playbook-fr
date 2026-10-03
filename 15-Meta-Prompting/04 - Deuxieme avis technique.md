---
titre: "Obtenir un second avis"
format: prompt
archetype: workflow
domaine: meta-prompting
tags:
  - prompting
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
sortie_attendue: "prompt ou workflow plus robuste"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Obtenir un second avis

## Quand l'utiliser

Pour décision importante.

## Prompt prêt à copier

```text
Analyse cette décision comme si tu devais challenger une proposition déjà acceptée.

Cherche :
- hypothèses fragiles ;
- alternatives sous-évaluées ;
- coûts cognitifs ;
- complexité ;
- risques sécurité ;
- opération ;
- lock-in ;
- migration ;
- testabilité.

Ne sois pas contrariant par principe.
Dis explicitement si la décision actuelle est raisonnable.

Sortie : prompt ou workflow plus robuste.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
