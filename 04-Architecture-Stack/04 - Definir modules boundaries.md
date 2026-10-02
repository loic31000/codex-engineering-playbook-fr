---
titre: "Définir modules et frontières"
type: prompt
tags:
  - architecture
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Définir modules et frontières

## Quand l'utiliser

Quand il faut structurer un monolithe ou des services.

## Prompt prêt à copier

```text
Propose des frontières de modules/bounded contexts à partir du domaine.

Pour chaque module :
- responsabilité ;
- données possédées ;
- API/contrats exposés ;
- dépendances autorisées ;
- dépendances interdites ;
- événements éventuels ;
- invariants métier.

Cherche les frontières métier avant les couches techniques.
Signale les zones où le découpage reste incertain.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
