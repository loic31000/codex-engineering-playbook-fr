---
titre: "Code review senior"
type: prompt
tags:
  - review
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Code review senior

## Quand l'utiliser

Avant merge ou après implémentation.

## Prompt prêt à copier

```text
Revois ce diff comme un reviewer senior.

Priorité :
1. bugs ;
2. sécurité ;
3. violation des critères d'acceptation ;
4. régression ;
5. architecture ;
6. data integrity ;
7. performance réelle ;
8. testabilité ;
9. maintenabilité.

Pour chaque finding :
- sévérité ;
- fichier/zone ;
- problème concret ;
- scénario d'échec ;
- correction minimale.

Ne produis pas de commentaires stylistiques sans impact.
```

## Sortie attendue

Une review priorisée et actionnable.
