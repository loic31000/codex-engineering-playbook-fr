---
titre: "Diagnostiquer un test flaky"
type: prompt
tags:
  - debug
  - maintenance
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
