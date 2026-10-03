---
titre: "Baseline sécurité"
format: prompt
archetype: instruction
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

# Baseline sécurité

## Quand l'utiliser

Au début du projet.

## Prompt prêt à copier

```text
Construis la baseline sécurité minimale de ce projet.

Évalue :
- exposition Internet ;
- auth ;
- autorisation ;
- données personnelles/sensibles ;
- secrets ;
- dépendances ;
- uploads ;
- webhooks ;
- API publique ;
- multi-tenancy ;
- admin ;
- logs ;
- CI/CD ;
- sauvegarde.

Pour chaque domaine :
- applicable ou N/A ;
- risque ;
- contrôle minimal ;
- vérification.

Reste proportionné au risque.

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
