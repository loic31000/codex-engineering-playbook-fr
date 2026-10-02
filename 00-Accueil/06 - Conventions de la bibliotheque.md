# Conventions de la bibliothèque

## Langue

Tous les prompts sont en français.

Les termes techniques largement utilisés peuvent rester en anglais lorsqu’ils sont plus précis :

- Story
- Epic
- scope
- review
- merge
- rollback
- threat model
- design system
- tokens
- etc.

## Nom des fichiers

```text
NN - Nom explicite.md
```

## Frontmatter

Pour les prompts :

```yaml
---
titre: "Nom"
type: prompt
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
tags:
  - domaine
---
```

## Structure recommandée

```text
# Titre

## Quand l'utiliser

## Prompt prêt à copier

## Sortie attendue

## Points de contrôle
```

## Une fiche = un objectif

Éviter un fichier qui mélange :

- architecture ;
- implémentation ;
- tests ;
- review ;
- release.

Préférer plusieurs prompts composables.

## Incertitude

Toujours préserver la différence :

```text
confirmé
hypothèse
indécis
N/A
```

## Sécurité

Aucun prompt ne doit demander un secret réel.

## User Stories

Ne pas mettre de coût financier dans une User Story.

Les estimations d’effort relatif peuvent exister si utiles.
