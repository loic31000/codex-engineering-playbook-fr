---
titre: "Planifier upgrade dépendances"
type: prompt
tags:
  - debug
  - maintenance
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Planifier upgrade dépendances

## Quand l'utiliser

Avant mise à jour majeure.

## Prompt prêt à copier

```text
Prépare l'upgrade de ces dépendances.

Pour chacune :
- version actuelle/cible ;
- breaking changes ;
- dépréciations ;
- sécurité ;
- code affecté ;
- migration ;
- tests ;
- ordre ;
- rollback.

Évite les upgrades majeurs groupés sans nécessité.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
