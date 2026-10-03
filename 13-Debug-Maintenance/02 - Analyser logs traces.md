---
titre: "Analyser logs et traces"
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

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
