---
titre: "Review finale avant merge"
format: prompt
archetype: checklist
domaine: review-convergence
tags:
  - review
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
sortie_attendue: "review priorisée et actionnable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
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
- BLOCKED avec bloquants précis.

Ne donne pas MERGEABLE si un vérification requis est inconnu.

Sortie : review priorisée et actionnable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une review priorisée et actionnable.
