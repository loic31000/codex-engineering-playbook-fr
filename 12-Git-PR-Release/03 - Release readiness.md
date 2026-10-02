---
titre: "Release readiness"
type: prompt
tags:
  - git
  - release
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
