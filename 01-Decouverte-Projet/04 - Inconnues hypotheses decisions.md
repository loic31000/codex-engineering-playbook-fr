---
titre: "Cartographier inconnues, hypothèses et décisions"
format: prompt
archetype: instruction
domaine: decouverte
tags:
  - decision-management
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
sortie_attendue: "registre de connaissance clair et exploitable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
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

Sortie : registre de connaissance clair et exploitable.
```

## Sortie attendue

Un registre de connaissance clair et exploitable.

## Points de contrôle

- [ ] Pas de mélange entre hypothèse et décision
- [ ] Chaque indécision a une question précise
