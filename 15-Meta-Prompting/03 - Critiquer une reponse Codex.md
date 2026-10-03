---
titre: "Critiquer une réponse Codex"
format: prompt
archetype: checklist
domaine: meta-prompting
tags:
  - prompting
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
sortie_attendue: "prompt ou workflow plus robuste"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Critiquer une réponse Codex

## Quand l'utiliser

Quand tu veux une seconde passe.

## Prompt prêt à copier

```text
Agis comme un reviewer indépendant.

Évalue cette réponse de Codex selon :
- respect de la demande ;
- faits non justifiés ;
- hypothèses cachées ;
- scope creep ;
- sécurité ;
- architecture ;
- testabilité ;
- omissions ;
- qualité de la sortie.

Ne réécris pas immédiatement.
Commence par les problèmes les plus importants, puis propose les corrections.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un prompt ou workflow plus robuste.
