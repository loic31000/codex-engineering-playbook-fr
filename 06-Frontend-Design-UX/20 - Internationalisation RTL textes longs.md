---
titre: "Internationalisation, RTL et textes longs"
format: prompt
archetype: checklist
domaine: frontend-design-ux
tags:
  - frontend
  - ux
  - i18n
  - rtl
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
  - interface-ou-composants
  - locales-cibles-si-connues
sortie_attendue: "Risques i18n et RTL avec corrections et scénarios de test"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Internationalisation, RTL et textes longs

## Quand l'utiliser

Pour vérifier qu'une interface reste utilisable avec plusieurs langues, des textes longs ou une direction RTL.

## Prompt prêt à copier

```text
Revois cette interface pour l'internationalisation.

Vérifie :
- chaînes non externalisées ;
- concaténations fragiles ;
- pluriels, dates, nombres, devises et fuseaux ;
- expansion de texte ;
- labels et boutons longs ;
- troncature ;
- layouts flexibles ;
- ordre logique et direction RTL ;
- icônes directionnelles ;
- formulaires ;
- tableaux et contenus denses.

Pour chaque constat :
- locale ou scénario concerné ;
- preuve ;
- impact utilisateur ;
- correction ;
- test de vérification.

N'invente pas les locales cibles : marque-les « à clarifier » si elles conditionnent la décision.
```

## Sortie attendue

Une review i18n/RTL directement exploitable.
