---
titre: "Implémenter une Story"
format: prompt
archetype: workflow
domaine: implementation
tags:
  - implementation
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
sortie_attendue: "implémentation contrôlée, testée et dans le scope"
niveau_risque: eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Implémenter une Story

## Quand l'utiliser

Après Story READY.

## Prompt prêt à copier

```text
Implémente uniquement la Story fournie.

Contexte à utiliser :
- la Story et ses critères d'acceptation ;
- le plan s'il existe ;
- les conventions et fichiers du repository réellement pertinents.

Avant de modifier le code, identifie seulement les ambiguïtés qui changeraient matériellement le comportement, la sécurité, les données ou un contrat public. S'il n'y en a pas, continue sans demander de confirmation.

Pendant l'implémentation :
- reste dans le scope ;
- respecte l'architecture et les conventions existantes ;
- préfère le changement minimal suffisant ;
- n'ajoute pas de dépendance sans le signaler ;
- n'affaiblis ni sécurité ni couverture de tests.

Validation :
- exécute les tests directement affectés et les vérifications obligatoires du projet ;
- mappe chaque critère d'acceptation vers le code et/ou le test qui le vérifie.

Sortie finale :
- résumé du changement ;
- critères d'acceptation couverts ;
- fichiers principaux modifiés ;
- tests exécutés et résultat ;
- hypothèses ou décisions restantes.

Si une décision métier ou de sécurité indispensable manque, arrête uniquement la partie concernée et explique ce qui doit être décidé.
```

## Sortie attendue

Une implémentation contrôlée, testée et dans le scope.
