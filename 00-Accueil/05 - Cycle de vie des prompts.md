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

```yaml
statut: draft
tests_reels: 0
cas_reussis: 0
derniere_validation: null
```

## testing

Le prompt est utilisé sur de vrais projets. Documenter au minimum :

- cas nominal ;
- contexte incomplet ;
- edge case ;
- cas adversarial ou contenu non fiable ;
- second projet ou stack différente si pertinent.

Pendant cette phase, noter ambiguïté, scope creep, contraintes ignorées, format instable, verbosité inutile et dépendance excessive à une stack.

## stable

Un prompt peut devenir stable lorsqu'il est suffisamment éprouvé :

- minimum 3 utilisations réelles ;
- si possible au moins 2 contextes ou projets ;
- aucun échec critique connu ;
- sortie suffisamment reproductible ;
- cas incomplet et cas limite testés ;
- limitations comprises.

```yaml
statut: stable
version: "1.0.0"
tests_reels: 3
derniere_validation: YYYY-MM-DD
```

## Revalidation

`stable` n'est pas permanent. Repasser un prompt en `testing` après :

- changement majeur de modèle ;
- changement de standard ou norme ;
- régression observée ;
- modification importante du prompt ;
- nouveau type de contexte qui révèle une faiblesse.

## deprecated

Conserver la fiche pour historique et indiquer le remplacement :

```markdown
> Déprécié : utiliser [[Chemin/Nouveau prompt]].
```

## Principe

La maturité n'est pas liée à la longueur. Un prompt court et fiable vaut mieux qu'un prompt complexe jamais réellement testé.
