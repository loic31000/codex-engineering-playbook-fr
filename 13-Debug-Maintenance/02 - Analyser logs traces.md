---
titre: "Analyser logs et traces"
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

# Analyser logs et traces

## Quand l'utiliser

Pour incident ou erreur distribuée.

## Prompt prêt à copier

```text
Analyse ces logs/traces comme un enquêteur.

Construis :
- timeline ;
- corrélation requests/jobs ;
- premier signal anormal ;
- erreurs secondaires ;
- dépendance fautive possible ;
- trous d'observabilité ;
- hypothèses ;
- prochaines vérifications.

Ne confonds pas dernière erreur visible et cause racine.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
