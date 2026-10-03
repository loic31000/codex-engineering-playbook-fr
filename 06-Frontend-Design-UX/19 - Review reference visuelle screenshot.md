---
titre: "Review à partir d'une référence visuelle"
format: prompt
archetype: checklist
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
  - screenshot-ou-reference
  - implementation-actuelle
sortie_attendue: "Écarts visuels priorisés avec preuves et corrections"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Review à partir d'une référence visuelle

## Quand l'utiliser

Quand une capture, maquette ou référence visuelle doit être comparée à l'interface implémentée.

## Prompt prêt à copier

```text
Compare la référence visuelle fournie à l'interface actuelle.

Évalue :
- structure et hiérarchie ;
- spacing et alignements ;
- typographie ;
- couleurs et contrastes ;
- composants ;
- densité ;
- états interactifs visibles ;
- responsive si plusieurs vues sont disponibles.

Pour chaque écart :
- preuve observable ;
- impact sur cohérence ou usage ;
- priorité ;
- correction minimale.

Distingue les différences intentionnelles, les écarts confirmés et les éléments impossibles à vérifier.
Ne copie pas aveuglément une référence si elle contredit les contraintes produit ou d'accessibilité.
```

## Sortie attendue

Une review visuelle priorisée et actionnable.
