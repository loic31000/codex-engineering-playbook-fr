---
titre: "Optimiser Core Web Vitals"
format: prompt
archetype: instruction
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

# Optimiser Core Web Vitals

## Quand l'utiliser

Quand une app web doit rester rapide.

## Prompt prêt à copier

```text
Analyse cette page sous l'angle performance utilisateur.

Cible les métriques Core Web Vitals :
- LCP ;
- INP ;
- CLS.

Analyse :
- poids JS ;
- code splitting ;
- hydratation ;
- rendu serveur/client ;
- images/fonts ;
- critical CSS ;
- requêtes ;
- cache ;
- third-party ;
- longues tâches ;
- handlers ;
- layout shifts ;
- lazy loading ;
- préchargement.

Classe :
- causes probables ;
- mesures à collecter ;
- optimisations à forte valeur ;
- optimisations prématurées à éviter.

Ne prétends pas résoudre un problème de performance sans mesure.

Sortie : recommandation frontend/design directement exploitable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une recommandation frontend/design directement exploitable.
