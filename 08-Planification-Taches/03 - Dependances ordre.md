---
titre: "Analyser dépendances et ordre"
type: prompt
tags:
  - planning
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Analyser dépendances et ordre

## Quand l'utiliser

Quand plusieurs tâches peuvent se bloquer.

## Prompt prêt à copier

```text
Construis le graphe de dépendances de ces tâches.

Pour chaque tâche :
- dépend de ;
- bloque ;
- peut être parallèle ;
- risque ;
- preuve de completion.

Propose un ordre qui maximise :
- feedback rapide ;
- réduction du risque ;
- travail parallèle ;
- disponibilité des fondations.
```

## Sortie attendue

Un plan/tâches actionnables.
