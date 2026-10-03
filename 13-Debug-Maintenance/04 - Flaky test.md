---
titre: "Diagnostiquer un test flaky"
format: prompt
archetype: workflow
domaine: debug-maintenance
tags:
  - debug
  - maintenance
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
sortie_attendue: "diagnostic ou plan de maintenance fondé sur des preuves"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Diagnostiquer un test flaky

## Quand l'utiliser

Quand un test passe/échoue aléatoirement.

## Prompt prêt à copier

```text
Analyse ce test flaky.

Cherche :
- temps ;
- ordre ;
- état partagé ;
- concurrence ;
- réseau ;
- random ;
- timezone ;
- ressources ;
- race condition ;
- cleanup ;
- isolation DB ;
- assertions asynchrones.

Propose d'abord comment reproduire/amplifier le problème, puis le correctif.

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
