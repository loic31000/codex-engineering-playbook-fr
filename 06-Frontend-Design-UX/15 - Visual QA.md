---
titre: "Visual QA frontend"
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
---

# Visual QA frontend

## Quand l'utiliser

Après implémentation d'un écran ou avant PR.

## Prompt prêt à copier

```text
Agis comme un designer produit + frontend reviewer.

Compare l'implémentation aux exigences visuelles et UX disponibles.

Vérifie :
- hiérarchie ;
- alignements ;
- spacing ;
- typographie ;
- couleurs ;
- radius/borders/shadows ;
- iconographie ;
- dimensions ;
- responsive ;
- overflow ;
- états ;
- focus ;
- hover ;
- disabled ;
- erreurs ;
- empty/loading ;
- cohérence avec le design system.

Classe :
- divergence fonctionnelle ;
- divergence visuelle majeure ;
- polish mineur.

Ne propose pas de redesign si l'implémentation respecte déjà la spec.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
