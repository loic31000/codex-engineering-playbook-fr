---
titre: "Préparer une Pull Request"
format: prompt
archetype: checklist
domaine: git-release
tags:
  - git
  - release
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
sortie_attendue: "artefact Git/release prêt à l'emploi"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Préparer une Pull Request

## Quand l'utiliser

Après tests et convergence.

## Prompt prêt à copier

```text
Prépare le contenu d'une PR claire.

Inclure :
- pourquoi ;
- ce qui change ;
- ce qui ne change pas ;
- Story/Epic associée ;
- décisions techniques importantes ;
- migrations ;
- sécurité ;
- tests exécutés ;
- screenshots/visual QA si frontend ;
- risques ;
- rollback si nécessaire ;
- checklist reviewer.

Reste concis et facilite la revue.

Sortie : artefact Git/release prêt à l'emploi.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
