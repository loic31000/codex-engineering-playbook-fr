---
titre: "Code review senior"
format: prompt
archetype: checklist
domaine: review-convergence
tags:
  - review
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
sortie_attendue: "review priorisée et actionnable"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Code review senior

## Quand l'utiliser

Avant merge ou après implémentation.

## Prompt prêt à copier

```text
Revois uniquement le diff fourni comme reviewer senior.

Priorise :
bugs, sécurité, critères d'acceptation, régressions, intégrité des données, contrats publics, architecture, performance significative et tests manquants.

Pour chaque constat, retourne :
- sévérité : critique / haute / moyenne / faible ;
- fichier et zone concernée ;
- preuve observable dans le diff ;
- scénario concret de défaillance ;
- correction minimale recommandée ;
- test ou vérification permettant de confirmer la correction.

Distingue explicitement :
- défaut confirmé ;
- risque plausible à vérifier.

N'invente pas un défaut sans preuve suffisante.
Ne signale pas de préférence stylistique sans impact réel.

S'il n'y a aucun problème significatif, dis-le explicitement.
```

## Sortie attendue

Une review priorisée et actionnable.
