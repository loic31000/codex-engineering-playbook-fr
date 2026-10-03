---
titre: "Security review d'une feature"
format: prompt
archetype: checklist
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

# Security review d'une feature

## Quand l'utiliser

Avant implémentation ou merge.

## Prompt prêt à copier

```text
Effectue une review sécurité ciblée de la feature et du diff fournis.

Analyse seulement les surfaces réellement touchées.
Selon leur pertinence, vérifie :
authentification, autorisation, validation, injections, SSRF, données sensibles, isolation tenant, uploads, webhooks, secrets, dépendances, logs, rate limiting et fonctions admin.

Pour chaque constat :
- sévérité ;
- statut : confirmé / probable / à vérifier ;
- preuve ;
- préconditions d'exploitation ;
- scénario d'abus ;
- impact ;
- mitigation minimale ;
- test de sécurité ou méthode de vérification.

Ne demande et n'affiche aucun secret réel.
Ne crée pas de vulnérabilité théorique sans chemin d'exploitation plausible.

Si une correction implique une action externe, destructive ou sensible, signale-la avant exécution et demande validation.
```

## Sortie attendue

Une analyse sécurité ciblée avec vérifications.
