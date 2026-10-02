# Cycle de vie des prompts

Chaque prompt évolue progressivement.

```text
draft
  ↓
testing
  ↓
stable
  ↓
deprecated
```

## draft

Idée suffisamment structurée pour être essayée.

Métadonnées :

```yaml
statut: draft
version: "0.1.0"
test_reel: false
```

## testing

Le prompt est utilisé sur de vrais projets.

```yaml
statut: testing
test_reel: true
```

Pendant cette phase, note les problèmes :

- ambiguïté ;
- sortie trop longue ;
- oubli fréquent ;
- scope creep ;
- mauvaise compréhension ;
- contraintes ignorées ;
- comportement trop spécifique à une stack.

## stable

Un prompt peut devenir stable lorsqu’il est suffisamment éprouvé.

Recommandation :

- minimum 3 utilisations réelles ;
- résultats utiles dans plusieurs contextes ;
- aucune faiblesse critique connue ;
- sortie attendue reproductible ;
- limitations comprises.

```yaml
statut: stable
version: "1.0.0"
test_reel: true
```

## deprecated

Le prompt existe encore pour historique mais un autre workflow doit être préféré.

Ajouter :

```markdown
> Déprécié : utiliser [[Chemin/Nouveau prompt]].
```

## Principe

La maturité n’est pas liée à la longueur ou à la sophistication du prompt.

Un prompt court et fiable vaut mieux qu’un prompt complexe jamais réellement testé.
