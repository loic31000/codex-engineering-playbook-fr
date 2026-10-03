---
titre: "Bootstrap projet"
format: prompt
archetype: workflow
domaine: decouverte
tags:
  - discovery
  - bootstrap
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
sortie_attendue: "carte complète mais concise du projet, avec incertitudes explicites"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Bootstrap projet

## Quand l'utiliser

Au tout début d'un nouveau projet ou lorsque le contexte existant est insuffisant.

## Prompt prêt à copier

```text
Agis comme un architecte produit et logiciel chargé de cadrer ce projet avant toute implémentation.

Mène une interview progressive en français.

Travaille par groupes de 3 à 5 questions maximum.

Couvre uniquement les domaines pertinents :
- problème produit ;
- utilisateurs ;
- scope et hors scope ;
- UX/UI ;
- architecture ;
- frontend/backend ;
- données ;
- authentification/autorisation ;
- sécurité et vie privée ;
- intégrations ;
- infrastructure ;
- observabilité ;
- tests ;
- Git/CI ;
- workflow de développement.

Pour chaque décision importante, utilise un état :
- confirmé ;
- hypothèse ;
- indécis ;
- N/A.

N'invente jamais une décision manquante.
Si tu recommandes quelque chose, marque-le comme proposition tant que je ne l'ai pas validé.

À la fin, produis :
1. décisions confirmées ;
2. hypothèses ;
3. décisions encore indécises ;
4. risques ;
5. documents à créer ;
6. bloquants avant spécification.
```

## Sortie attendue

Une carte complète mais concise du projet, avec incertitudes explicites.

## Points de contrôle

- [ ] Aucune implémentation commencée
- [ ] Aucune hypothèse transformée en décision
- [ ] Les risques sécurité sont identifiés
