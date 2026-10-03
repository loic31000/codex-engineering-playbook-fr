---
titre: "Rédiger un postmortem"
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

# Rédiger un postmortem

## Quand l'utiliser

Après incident.

## Prompt prêt à copier

```text
Rédige un postmortem sans blâme.

Structure :
- résumé ;
- impact ;
- timeline ;
- détection ;
- réponse ;
- cause racine ;
- facteurs contributifs ;
- ce qui a bien fonctionné ;
- ce qui a mal fonctionné ;
- actions correctives ;
- owner/priorité ;
- mesures de prévention.

Distingue cause racine et déclencheur.

Sortie : diagnostic ou plan de maintenance fondé sur des preuves.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un diagnostic ou plan de maintenance fondé sur des preuves.
