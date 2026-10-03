---
titre: "Review isolation multi-tenant"
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

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
