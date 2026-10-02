---
titre: "Visual QA frontend"
type: prompt
tags:
  - frontend
  - design
  - ux
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
