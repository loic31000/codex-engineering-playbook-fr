---
titre: "Secrets et supply chain"
format: prompt
archetype: instruction
domaine: securite-privacy
tags:
  - security
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
sortie_attendue: "analyse sécurité ciblée avec vérifications"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Secrets et supply chain

## Quand l'utiliser

Avant merge ou ajout d'une dépendance.

## Prompt prêt à copier

```text
Revois cette modification sous l'angle secrets et supply chain.

Vérifie :
- aucun secret hardcodé ;
- variables/config ;
- logs ;
- CI ;
- permissions tokens ;
- nouvelle dépendance ;
- réputation/maintenance ;
- version ;
- lockfile ;
- transitive deps ;
- vulnérabilités ;
- scripts d'installation ;
- licence si pertinente.

Classe les problèmes par sévérité.

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
