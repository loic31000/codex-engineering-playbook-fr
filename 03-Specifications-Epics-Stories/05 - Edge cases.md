---
titre: "Trouver les edge cases"
format: prompt
archetype: instruction
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
sortie_attendue: "liste d'edge cases priorisée"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : liste d'edge cases priorisée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une liste d'edge cases priorisée.
