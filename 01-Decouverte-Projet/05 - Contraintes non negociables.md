---
titre: "Identifier les contraintes non négociables"
format: prompt
archetype: instruction
domaine: decouverte
tags:
  - constraints
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
sortie_attendue: "contrat de contraintes clair"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Identifier les contraintes non négociables

## Quand l'utiliser

Quand tu veux distinguer les vraies contraintes des préférences.

## Prompt prêt à copier

```text
Analyse les contraintes exprimées pour ce projet.

Classe chacune dans :
- obligation réglementaire ;
- obligation métier ;
- contrainte technique ;
- contrainte organisationnelle ;
- compatibilité ;
- sécurité ;
- préférence seulement.

Pour chaque contrainte :
- reformule-la précisément ;
- indique sa source ;
- indique ce qu'elle interdit ;
- indique ce qu'elle laisse ouvert ;
- signale toute contradiction.

Termine par une liste « non négociable » séparée des préférences.

Sortie : contrat de contraintes clair.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Un contrat de contraintes clair.

## Points de contrôle

- [ ] Préférences séparées des obligations
- [ ] Contradictions visibles
