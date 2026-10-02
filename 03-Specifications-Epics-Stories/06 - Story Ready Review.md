---
titre: "Story Ready Review"
type: prompt
tags:
  - spec
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
- blockers ;
- points non bloquants ;
- décisions/questions requises ;
- recommandation : plan formel nécessaire ou non.
```

## Sortie attendue

Une décision de readiness argumentée.
