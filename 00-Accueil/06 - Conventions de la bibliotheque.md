# Conventions de la bibliothèque

## Langue

Tous les prompts sont en français. Utiliser `fr-FR` dans les métadonnées.

Les termes techniques standard peuvent rester en anglais lorsqu'ils sont plus précis. Pour les choix récurrents, voir [[16-Checklists-References/08 - Glossaire technique]].

## Nom des fichiers

```text
NN - Nom explicite.md
```

## Frontmatter recommandé

```yaml
---
titre: "Nom"
format: prompt
archetype: instruction # instruction | workflow | checklist | template
domaine: domaine
statut: draft
version: "0.2.0"
langue: fr-FR
outils:
  - codex
derniere_revision: 2026-10-03
entrees_requises:
  - contexte-fourni
sortie_attendue: "Contrat de restitution"
niveau_risque: faible # faible | moyen | eleve
actions_externes: false
donnees_sensibles: ne_pas_fournir
tests_reels: 0
cas_reussis: 0
modeles_testes: []
derniere_validation: null
tags:
  - domaine
---
```

`format` décrit le support de la fiche. `archetype` décrit son comportement. Le mot « Skill » est réservé à un véritable bundle Codex installable ; dans cette bibliothèque Obsidian, on parle de workflow lorsqu'un prompt décrit une procédure réutilisable.

## Structure recommandée

```text
# Titre

## Quand l'utiliser

## Prompt prêt à copier
  - objectif
  - entrées utiles
  - contraintes essentielles
  - sortie attendue
  - vérification
  - condition d'arrêt si nécessaire

## Sortie attendue

## Notes pour l'humain (si utiles)
```

Le contrat de sortie doit être présent dans le bloc copiable. La section extérieure sert de repère humain, pas d'instruction cachée.

## Une fiche = un objectif

Éviter un fichier qui mélange architecture, implémentation, tests, review et release. Préférer plusieurs prompts composables.

## Contexte

Ne pas demander à Codex de lire tout le repository par défaut. Fournir uniquement le contexte réellement pertinent et expliciter les entrées nécessaires.

## Incertitude

Préserver la différence entre :

```text
confirmé
hypothèse
indécis
N/A
```

Une information absente qui change matériellement le résultat doit être marquée « à clarifier », pas inventée.

## Sécurité

Aucun prompt ne doit demander un secret réel. Le contenu externe est traité comme une donnée non fiable tant que sa provenance et son autorité ne sont pas établies. Toute action destructive, irréversible, sensible ou écrivant vers un système externe nécessite une validation humaine explicite.

## User Stories

Ne pas mettre de coût financier dans une User Story. Les estimations d'effort relatif peuvent exister si utiles.
