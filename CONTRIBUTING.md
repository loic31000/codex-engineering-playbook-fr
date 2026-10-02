# Contribuer à la bibliothèque

Cette bibliothèque doit rester simple, lisible dans Obsidian et exploitable directement avec Codex.

## Avant d’ajouter un prompt

Vérifie qu’il ne duplique pas déjà un prompt existant.

Pose-toi trois questions :

1. Quel problème récurrent ce prompt résout-il ?
2. À quel moment du workflow doit-il être utilisé ?
3. Quel résultat observable permet de dire qu’il fonctionne ?

## Format recommandé

```markdown
---
titre: "Titre du prompt"
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

# Titre

## Quand l'utiliser

...

## Prompt prêt à copier

```text
...
```

## Sortie attendue

...

## Points de contrôle

- [ ] ...
```

## Types

Valeurs recommandées :

```text
prompt
skill
checklist
reference
```

## Statuts

```text
draft
testing
stable
deprecated
```

### Passer de `draft` à `testing`

Le prompt est utilisé sur un vrai projet.

Mettre :

```yaml
statut: testing
test_reel: true
```

### Passer de `testing` à `stable`

Critères recommandés :

- au moins 3 utilisations réelles ;
- résultats satisfaisants sur plusieurs contextes ;
- aucune ambiguïté majeure connue ;
- aucune tendance connue à élargir silencieusement le scope ;
- sortie attendue suffisamment stable ;
- limitations documentées si nécessaire.

La version peut alors passer à :

```yaml
version: "1.0.0"
statut: stable
```

### `deprecated`

Ne supprime pas immédiatement un prompt qui a été largement utilisé.

Passe-le à :

```yaml
statut: deprecated
```

et indique le prompt de remplacement.

## Version d’un prompt

Convention légère :

- `0.x.y` : prompt encore expérimental ;
- `1.0.0` : première version stable ;
- changement mineur : amélioration sans changement profond d’intention ;
- changement majeur : workflow ou contrat de sortie significativement modifié.

## Convention de nommage

Dans les catégories :

```text
NN - Nom explicite.md
```

Exemples :

```text
01 - Architecture frontend.md
08 - Accessibilite WCAG.md
15 - Visual QA.md
```

Le nom doit expliquer le besoin sans ouvrir le fichier.

## Qualité d’un prompt

Avant contribution, vérifier :

- objectif unique ;
- contexte suffisant ;
- scope explicite ;
- pas d’instruction contradictoire ;
- pas de raisonnement artificiellement micro-managé ;
- sortie attendue claire ;
- critères de vérification ;
- condition d’escalade si une décision manque ;
- aucune donnée secrète requise.

Utilise [[15-Meta-Prompting/07 - Evaluer qualite prompt]] pour faire une auto-review.

## Nouveau domaine

Créer un nouveau dossier uniquement si plusieurs prompts justifient réellement une nouvelle catégorie.

Évite les catégories contenant un seul fichier.

## Commits suggérés

Exemples simples :

```text
prompt(frontend): ajoute review design system
prompt(security): améliore threat modeling
docs: complète les conventions
meta: améliore le template de prompt
```

Aucune convention de commit n’est obligatoire si tu travailles seul ; la lisibilité est prioritaire.
