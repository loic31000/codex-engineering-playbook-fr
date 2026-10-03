---
titre: "Review d'architecture"
format: prompt
archetype: checklist
domaine: architecture
tags:
  - architecture
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
sortie_attendue: "analyse ou décision architecturale structurée"
niveau_risque: moyen
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Review d'architecture

## Quand l'utiliser

Après une proposition ou sur un projet existant.

## Prompt prêt à copier

```text
Revois cette architecture comme un architecte critique.

Évalue :
- cohésion des modules ;
- couplage ;
- dépendances ;
- sens des dépendances ;
- frontières métier ;
- persistance ;
- contrats ;
- sécurité ;
- observabilité ;
- testabilité ;
- déploiement ;
- failure modes ;
- complexité accidentelle.

Identifie :
- risques ;
- sur-ingénierie ;
- dette probable ;
- éléments non justifiés ;
- décisions nécessitant un ADR.

Ne propose pas de microservices par défaut.

Sortie : analyse ou décision architecturale structurée.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
