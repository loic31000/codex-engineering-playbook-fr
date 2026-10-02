---
titre: "Identifier les contraintes non négociables"
type: prompt
tags:
  - constraints
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Un contrat de contraintes clair.

## Points de contrôle

- [ ] Préférences séparées des obligations
- [ ] Contradictions visibles
