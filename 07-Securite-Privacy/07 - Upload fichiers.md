---
titre: "Sécuriser les uploads"
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
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
