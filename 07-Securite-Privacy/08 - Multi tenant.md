---
titre: "Review isolation multi-tenant"
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

# Review isolation multi-tenant

## Quand l'utiliser

Pour SaaS multi-tenant.

## Prompt prêt à copier

```text
Analyse l'isolation multi-tenant de bout en bout.

Vérifie :
- tenant context ;
- requêtes DB ;
- caches ;
- jobs async ;
- fichiers ;
- search ;
- logs ;
- API ;
- admin ;
- exports ;
- webhooks ;
- analytics ;
- tests.

Cherche les accès cross-tenant possibles.
Propose des tests dédiés d'isolation.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
