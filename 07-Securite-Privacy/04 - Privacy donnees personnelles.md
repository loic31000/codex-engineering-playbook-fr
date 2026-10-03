---
titre: "Privacy et données personnelles"
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

# Privacy et données personnelles

## Quand l'utiliser

Quand le système traite des données personnelles.

## Prompt prêt à copier

```text
Analyse la feature fournie sous l'angle protection des données.

Cartographie :
- catégories de données ;
- source ;
- finalité déclarée ;
- stockage ;
- personnes/services ayant accès ;
- transferts ou partages ;
- logs et télémétrie ;
- durée de conservation ;
- suppression ;
- export ;
- sauvegardes ;
- environnements de test.

Recherche en priorité :
collecte excessive, données non nécessaires, fuite dans les logs, droits trop larges, rétention indéfinie et copies secondaires oubliées.

Pour chaque problème :
- donnée concernée ;
- risque ;
- minimisation ou contrôle technique proposé ;
- moyen de vérification.

Sépare :
- fait confirmé ;
- hypothèse ;
- information manquante ;
- décision juridique à faire valider.

N'invente jamais une base légale ou une conclusion de conformité.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
