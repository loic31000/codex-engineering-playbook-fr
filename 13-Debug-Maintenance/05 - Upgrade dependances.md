---
titre: "Planifier upgrade dépendances"
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

# Planifier upgrade dépendances

## Quand l'utiliser

Avant mise à jour majeure.

## Prompt prêt à copier

```text
Prépare l'upgrade de ces dépendances.

Pour chacune :
- version actuelle/cible ;
- breaking changes ;
- dépréciations ;
- sécurité ;
- code affecté ;
- migration ;
- tests ;
- ordre ;
- rollback.

Évite les upgrades majeurs groupés sans nécessité.

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
