---
titre: "Review finale avant merge"
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

# Review finale avant merge

## Quand l'utiliser

Dernier contrôle.

## Prompt prêt à copier

```text
Fais une review finale de merge.

Vérifie :
- Story READY et réalisée ;
- AC satisfaits ;
- tests ;
- lint/typecheck/build si applicables ;
- sécurité ;
- migrations ;
- API ;
- documentation ;
- ADR ;
- TODO/FIXME ;
- logs/secrets ;
- diff focalisé ;
- rollback si nécessaire.

Réponds :
- MERGEABLE ;
ou
- BLOCKED avec blockers précis.

Ne donne pas MERGEABLE si un check requis est inconnu.
```

## Sortie attendue

Une review priorisée et actionnable.
