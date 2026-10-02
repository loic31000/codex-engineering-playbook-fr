---
titre: "Secrets et supply chain"
type: prompt
tags:
  - security
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Secrets et supply chain

## Quand l'utiliser

Avant merge ou ajout d'une dépendance.

## Prompt prêt à copier

```text
Revois cette modification sous l'angle secrets et supply chain.

Vérifie :
- aucun secret hardcodé ;
- variables/config ;
- logs ;
- CI ;
- permissions tokens ;
- nouvelle dépendance ;
- réputation/maintenance ;
- version ;
- lockfile ;
- transitive deps ;
- vulnérabilités ;
- scripts d'installation ;
- licence si pertinente.

Classe les problèmes par sévérité.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
