---
titre: "Documenter architecture"
format: prompt
archetype: template
domaine: documentation
tags:
  - documentation
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
sortie_attendue: "documentation concise, actuelle et orientée usage"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Documenter architecture

## Quand l'utiliser

Après décision ou refonte.

## Prompt prêt à copier

```text
Rédige la documentation d'architecture actuelle.

Inclure :
- contexte ;
- diagramme textuel si utile ;
- modules ;
- flux ;
- données ;
- intégrations ;
- auth ;
- sécurité ;
- déploiement ;
- observabilité ;
- contraintes ;
- ADR liés.

Documente l'état réel, pas l'état souhaité.

Sortie : documentation concise, actuelle et orientée usage.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une documentation concise, actuelle et orientée usage.
