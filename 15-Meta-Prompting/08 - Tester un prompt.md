---
titre: "Tester un prompt"
format: prompt
archetype: checklist
domaine: meta-prompting
tags:
  - meta
  - eval
  - prompt
statut: draft
version: "0.1.0"
langue: fr-FR
outils:
  - codex
tests_reels: 0
cas_reussis: 0
modeles_testes: []
derniere_validation: null
derniere_revision: 2026-10-03
entrees_requises:
  - prompt-a-tester
  - scenarios-de-test
sortie_attendue: "Évaluation reproductible du prompt et modifications justifiées par des échecs observés"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Tester un prompt

## Quand l'utiliser

Avant de faire passer un prompt de `draft` à `testing`, ou après une modification importante.

## Prompt prêt à copier

```text
Teste ce prompt sur plusieurs scénarios sans le réécrire immédiatement.

Évalue :
- déclenchement correct ;
- objectif accompli ;
- respect du contexte ;
- respect du scope ;
- gestion des informations manquantes ;
- format de sortie ;
- vérifiabilité ;
- sécurité ;
- verbosité inutile.

Sépare :
- problème du prompt ;
- problème du contexte fourni ;
- erreur du modèle ;
- préférence subjective.

Utilise au minimum :
- un cas nominal ;
- un contexte incomplet ;
- un edge case ;
- un cas adversarial ou contenu non fiable ;
- un second projet ou une stack différente si pertinent.

Propose une modification uniquement lorsqu'un échec est reproductible ou qu'un critère important manque.
```

## Sortie attendue

Un rapport de test avec scores, échecs observés et changements proposés.
