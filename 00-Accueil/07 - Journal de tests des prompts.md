# Journal de tests des prompts

Utilise cette note pour suivre les essais réels et comparer les versions.

## Cas minimaux recommandés

1. cas nominal ;
2. contexte incomplet ;
3. edge case ;
4. cas adversarial ou contenu non fiable ;
5. second projet ou stack différente si pertinent.

## Score par run

Noter chaque axe de 0 à 2 :

| Axe | 0 | 1 | 2 |
|---|---|---|---|
| Objectif accompli | échec | partiel | atteint |
| Respect du contexte | mauvais | moyen | bon |
| Respect du scope | déborde | quelques écarts | respecté |
| Qualité / vérifiabilité | faible | moyenne | forte |
| Format de sortie | non respecté | partiel | respecté |
| Sécurité / prudence | insuffisante | correcte | forte |

Interprétation indicative :

- 12/12 : excellent ;
- 10–11 : bon ;
- 8–9 : amélioration nécessaire ;
- < 8 : prompt à retravailler.

## Modèle de run

```markdown
### YYYY-MM-DD — Nom du prompt

Projet / contexte :
Type de cas :
Modèle / outil :
Version du prompt :

Score :
- objectif : /2
- contexte : /2
- scope : /2
- qualité / vérifiabilité : /2
- format : /2
- sécurité / prudence : /2
- total : /12

Résultat :
- bon :
- mauvais :
- ambigu :
- manquant :

Diagnostic :
- problème du prompt :
- problème du contexte :
- erreur du modèle :
- préférence subjective :

Action :
- garder ;
- modifier ;
- fusionner ;
- déprécier.
```

## Comparaison A/B

Lorsqu'un prompt change, comparer si possible l'ancienne et la nouvelle version avec le même contexte et le même modèle. Garder la version qui améliore les critères observables, pas celle qui paraît seulement plus élégante.

## Tests

_Aucun test réel enregistré pour le moment._
