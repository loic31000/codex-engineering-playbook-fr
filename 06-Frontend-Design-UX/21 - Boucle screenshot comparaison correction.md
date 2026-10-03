---
titre: "Boucle screenshot → comparaison → correction"
format: prompt
archetype: workflow
domaine: frontend-design-ux
tags:
  - frontend
  - design
  - visual-qa
statut: draft
version: "0.1.0"
langue: fr-FR
outils:
  - codex
tests_reels: 0
cas_reussis: 0
modeles_testes: []
derniere_validation: null
derniere_revision: 2026-10-03
entrees_requises:
  - reference-visuelle
  - screenshot-implementation
sortie_attendue: "Boucle de correction visuelle incrémentale avec vérification"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Boucle screenshot → comparaison → correction

## Quand l'utiliser

Quand une implémentation frontend doit converger progressivement vers une référence visuelle.

## Prompt prêt à copier

```text
Fais converger l'interface vers la référence visuelle par petites corrections vérifiables.

À chaque itération :
1. compare le screenshot actuel à la référence ;
2. identifie les 1 à 3 écarts les plus importants ;
3. propose ou applique la correction minimale ;
4. demande ou produis un nouveau screenshot si l'outil le permet ;
5. recompare avant de poursuivre.

Priorise structure, hiérarchie, spacing, typographie et responsive avant les détails décoratifs.

Ne change pas le comportement produit pour obtenir une simple ressemblance visuelle.
Respecte accessibilité et design system existants.

Sortie finale :
- écarts corrigés ;
- écarts restants ;
- différences intentionnelles ;
- vérifications effectuées.
```

## Sortie attendue

Une convergence visuelle incrémentale plutôt qu'une réécriture globale.
