---
titre: "Bootstrap projet"
type: prompt
tags:
  - discovery
  - bootstrap
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
6. blockers avant spécification.
```

## Sortie attendue

Une carte complète mais concise du projet, avec incertitudes explicites.

## Points de contrôle

- [ ] Aucune implémentation commencée
- [ ] Aucune hypothèse transformée en décision
- [ ] Les risques sécurité sont identifiés
