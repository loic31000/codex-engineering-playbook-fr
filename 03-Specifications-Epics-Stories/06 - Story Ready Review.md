---
titre: "Story Ready Review"
format: prompt
archetype: checklist
domaine: specifications
tags:
  - spec
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
sortie_attendue: "décision de readiness argumentée"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Story Ready Review

## Quand l'utiliser

Juste avant l'implémentation.

## Prompt prêt à copier

```text
Agis comme gatekeeper de Definition of Ready.

Évalue cette Story sans coder.

Vérifie :
- objectif ;
- scope ;
- critères d'acceptation ;
- edge cases ;
- dépendances ;
- décisions ouvertes ;
- architecture impactée ;
- data/migrations ;
- sécurité/privacy ;
- UX/UI ;
- API/contrats ;
- stratégie de test ;
- taille de la Story.

Réponds uniquement avec :
- READY ou BLOCKED ;
- bloquants ;
- points non bloquants ;
- décisions/questions requises ;
- recommandation : plan formel nécessaire ou non.

Sortie : décision de readiness argumentée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une décision de readiness argumentée.
