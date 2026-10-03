---
titre: "Détecter architecture drift"
format: prompt
archetype: checklist
domaine: review-convergence
tags:
  - review
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
sortie_attendue: "review priorisée et actionnable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Détecter architecture drift

## Quand l'utiliser

Pour vérifier qu'une feature n'érode pas les frontières.

## Prompt prêt à copier

```text
Compare ce changement à l'architecture documentée.

Cherche :
- dépendance inversée ;
- accès direct interdit ;
- logique métier dans mauvaise couche ;
- duplication de concepts ;
- dépendance circulaire ;
- nouvelle abstraction non documentée ;
- persistance traversant une frontière ;
- contournement d'API interne.

Classe :
- drift bloquant ;
- dette acceptable ;
- faux positif.

Sortie : review priorisée et actionnable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une review priorisée et actionnable.
