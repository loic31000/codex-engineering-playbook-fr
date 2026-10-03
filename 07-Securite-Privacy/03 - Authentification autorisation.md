---
titre: "Review auth et autorisation"
format: prompt
archetype: checklist
domaine: securite-privacy
tags:
  - security
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
sortie_attendue: "analyse sécurité ciblée avec vérifications"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
