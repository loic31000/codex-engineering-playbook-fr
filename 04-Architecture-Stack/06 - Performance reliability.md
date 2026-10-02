---
titre: "Architecture performance et résilience"
type: prompt
tags:
  - architecture
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
