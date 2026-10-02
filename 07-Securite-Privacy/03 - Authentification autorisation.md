---
titre: "Review auth et autorisation"
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

# Review auth et autorisation

## Quand l'utiliser

Pour login, rôles, permissions, multi-tenant.

## Prompt prêt à copier

```text
Revois ce design d'authentification/autorisation.

Vérifie :
- identité ;
- session/tokens ;
- expiration ;
- rotation ;
- MFA ;
- recovery ;
- CSRF si applicable ;
- stockage tokens ;
- logout ;
- authorization côté serveur ;
- object-level access ;
- tenant isolation ;
- deny by default ;
- admin ;
- audit.

Cherche explicitement les chemins de contournement d'autorisation.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
