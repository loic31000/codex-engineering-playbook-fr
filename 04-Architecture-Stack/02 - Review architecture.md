---
titre: "Review d'architecture"
type: prompt
tags:
  - architecture
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une analyse ou décision architecturale structurée.
