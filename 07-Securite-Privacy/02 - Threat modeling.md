---
titre: "Threat modeling"
format: prompt
archetype: checklist
domaine: securite-privacy
tags:
  - security
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
sortie_attendue: "analyse sécurité ciblée avec vérifications"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Threat modeling

## Quand l'utiliser

Pour une architecture ou feature sensible.

## Prompt prêt à copier

```text
Construis un threat model pragmatique.

Identifie :
- assets ;
- acteurs ;
- trust boundaries ;
- entry points ;
- flux de données ;
- dépendances externes ;
- menaces ;
- abus ;
- mitigations ;
- vérifications ;
- risques résiduels.

Priorise les scénarios plausibles.
Ne génère pas une checklist générique sans lien avec l'architecture.

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
