---
titre: "Review accessibilité WCAG 2.2"
format: prompt
archetype: checklist
domaine: frontend-design-ux
tags:
  - frontend
  - design
  - ux
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
sortie_attendue: "recommandation frontend/design directement exploitable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
standard:
  nom: "WCAG 2.2"
  niveau: "AA"
  derniere_verification: 2026-10-03
---

# Review accessibilité WCAG 2.2

## Quand l'utiliser

Pour une UI avant merge ou lors de la conception.

## Prompt prêt à copier

```text
Audite l'interface fournie avec WCAG 2.2, niveau AA par défaut.

Sépare strictement :
1. échecs de conformité WCAG ;
2. points impossibles à confirmer avec les éléments disponibles ;
3. bonnes pratiques d'accessibilité non bloquantes.

Examine notamment :
sémantique, headings, landmarks, labels, clavier, focus, ordre de focus, contrastes, zoom/reflow, cibles tactiles, alternatives textuelles, messages de statut, dialogs, formulaires, drag-and-drop, authentification accessible et animations.

Pour chaque échec potentiel, fournis :
- critère WCAG 2.2 et niveau lorsque tu peux l'identifier avec confiance ;
- preuve observée ;
- impact utilisateur ;
- méthode de reproduction ;
- correction minimale ;
- méthode de re-test.

Ne déclare pas une interface « conforme WCAG » lorsque certains critères nécessitent une vérification que tu ne peux pas effectuer.

Classe les résultats : bloquant / important / amélioration.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
