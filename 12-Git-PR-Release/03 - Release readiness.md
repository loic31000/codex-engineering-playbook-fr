---
titre: "Release readiness"
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

# Release readiness

## Quand l'utiliser

Avant production.

## Prompt prêt à copier

```text
Évalue si cette release est prête.

Vérifie :
- contenu exact ;
- migrations ;
- flags ;
- configuration ;
- secrets ;
- observabilité ;
- alertes ;
- rollback ;
- tests ;
- compatibilité ;
- documentation opératoire ;
- risques connus.

Réponds READY ou BLOCKED avec éléments précis.

Sortie : artefact Git/release prêt à l'emploi.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
