---
titre: "Sécuriser les uploads"
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

# Sécuriser les uploads

## Quand l'utiliser

Quand l'utilisateur peut envoyer des fichiers.

## Prompt prêt à copier

```text
Analyse le flux d'upload.

Vérifie :
- taille ;
- type réel ;
- extension ;
- nom ;
- stockage ;
- accès ;
- antivirus/sandbox si nécessaire ;
- contenu actif ;
- image processing ;
- path traversal ;
- URLs signées ;
- durée ;
- quotas ;
- métadonnées ;
- multi-tenancy ;
- suppression ;
- logs.

Propose une stratégie proportionnée au risque.

Sortie : analyse sécurité ciblée avec vérifications.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
