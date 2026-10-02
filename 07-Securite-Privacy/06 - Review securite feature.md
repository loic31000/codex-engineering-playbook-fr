---
titre: "Security review d'une feature"
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

# Security review d'une feature

## Quand l'utiliser

Avant implémentation ou merge.

## Prompt prêt à copier

```text
Fais une security review ciblée de cette feature.

Ne fais pas une checklist générique.

Analyse uniquement les surfaces réellement touchées :
- auth ;
- authorization ;
- validation ;
- injection ;
- data ;
- privacy ;
- uploads ;
- webhooks ;
- SSRF ;
- secrets ;
- dépendances ;
- logs ;
- rate limiting ;
- tenant isolation ;
- admin.

Pour chaque finding :
- sévérité ;
- scénario ;
- impact ;
- mitigation ;
- test/vérification.

Les problèmes critiques non résolus sont blockers.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
