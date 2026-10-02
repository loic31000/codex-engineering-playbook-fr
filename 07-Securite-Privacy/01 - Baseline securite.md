---
titre: "Baseline sécurité"
type: prompt
tags:
  - security
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
