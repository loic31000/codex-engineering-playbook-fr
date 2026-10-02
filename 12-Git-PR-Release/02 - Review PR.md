---
titre: "Review de PR"
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

# Review de PR

## Quand l'utiliser

Pour examiner une PR entière.

## Prompt prêt à copier

```text
Analyse cette PR dans son ensemble, pas seulement fichier par fichier.

Évalue :
- cohérence avec la Story ;
- taille/focus ;
- architecture ;
- sécurité ;
- data ;
- tests ;
- docs ;
- migration ;
- backward compatibility ;
- rollout ;
- observabilité.

Signale en premier les blockers.
```

## Sortie attendue

Un artefact Git/release prêt à l'emploi.
