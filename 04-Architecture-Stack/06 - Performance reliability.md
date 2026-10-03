---
titre: "Architecture performance et résilience"
format: prompt
archetype: instruction
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Architecture performance et résilience

## Quand l'utiliser

Quand la feature a des enjeux de charge, latence ou disponibilité.

## Prompt prêt à copier

```text
Analyse cette architecture sous l'angle performance et résilience.

Évalue :
- chemin critique ;
- latence ;
- débit ;
- contention ;
- cache ;
- I/O ;
- timeouts ;
- retries ;
- idempotence ;
- backpressure ;
- circuit breakers ;
- queues ;
- dégradation ;
- recovery ;
- observabilité.

N'optimise pas prématurément.
Sépare :
- risques démontrés ;
- risques plausibles ;
- optimisations à mesurer avant décision.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
