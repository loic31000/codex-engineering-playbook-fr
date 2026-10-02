# Anti-patterns de prompts

Évite :

## Le méga-prompt permanent
Trop de règles chargées pour chaque tâche.

## Le prompt « fais tout »
Analyse + architecture + code + tests + review dans un seul tour.

## Le raisonnement micro-managé
« Pense étape 1, puis étape 2, puis réfléchis encore... »

Préférer :
- objectif ;
- contexte ;
- contraintes ;
- sortie ;
- vérification.

## Les termes vagues
« propre », « intuitif », « performant », « sécurisé ».

Les transformer en critères observables.

## L'autorité implicite
Ne pas laisser Codex convertir une recommandation en décision projet.

## « Fais passer les tests »
Sans préciser qu'il ne doit pas affaiblir/supprimer les tests.

## L'absence de condition d'arrêt
Une décision manquante importante doit pouvoir bloquer la tâche.
