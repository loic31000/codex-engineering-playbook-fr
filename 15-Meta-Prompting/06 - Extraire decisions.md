---
titre: "Extraire les décisions d'une conversation"
type: prompt
tags:
  - prompting
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Extraire les décisions d'une conversation

## Quand l'utiliser

Après une longue session.

## Prompt prêt à copier

```text
À partir de cette conversation, extrais uniquement les décisions durables.

Pour chacune :
- décision ;
- état : confirmé/hypothèse/indécis ;
- justification ;
- conséquence ;
- document à mettre à jour ;
- besoin éventuel d'ADR.

Ne transforme pas une suggestion en décision confirmée.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
