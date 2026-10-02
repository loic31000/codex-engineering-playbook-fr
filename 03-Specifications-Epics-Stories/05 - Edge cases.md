---
titre: "Trouver les edge cases"
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

# Trouver les edge cases

## Quand l'utiliser

Avant de déclarer une Story prête.

## Prompt prêt à copier

```text
Analyse cette fonctionnalité exclusivement sous l'angle des edge cases.

Cherche :
- valeurs vides ;
- valeurs limites ;
- doublons ;
- concurrence ;
- retry ;
- timeouts ;
- permissions ;
- session expirée ;
- données supprimées/modifiées ;
- erreurs réseau ;
- état partiel ;
- idempotence ;
- multi-tenant ;
- timezone/locale ;
- mobile/responsive si UI.

Classe :
- à couvrir obligatoirement ;
- utile mais secondaire ;
- hors scope.

N'élargis pas automatiquement la Story.
```

## Sortie attendue

Une liste d'edge cases priorisée.
