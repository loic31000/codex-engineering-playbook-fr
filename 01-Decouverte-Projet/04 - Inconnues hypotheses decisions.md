---
titre: "Cartographier inconnues, hypothèses et décisions"
type: prompt
tags:
  - decision-management
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Cartographier inconnues, hypothèses et décisions

## Quand l'utiliser

Quand le projet semble avancer avec beaucoup de suppositions implicites.

## Prompt prêt à copier

```text
Analyse le contexte disponible et construis quatre listes distinctes :

1. CONFIRMÉ
Faits et décisions explicitement établis.

2. HYPOTHÈSES
Éléments utilisés pour avancer mais pas encore validés.

3. INDÉCIS
Décisions pertinentes qui n'ont pas encore été prises.

4. N/A
Sujets explicitement non applicables.

Pour chaque hypothèse ou décision indécise, indique :
- impact potentiel ;
- niveau de risque ;
- moment au plus tard où elle doit être résolue ;
- question exacte à poser.

Ne crée aucune nouvelle décision.
```

## Sortie attendue

Un registre de connaissance clair et exploitable.

## Points de contrôle

- [ ] Pas de mélange entre hypothèse et décision
- [ ] Chaque indécision a une question précise
