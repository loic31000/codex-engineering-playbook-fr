# Formule de prompt de référence

Un bon prompt de travail contient généralement :

```text
RÔLE
OBJECTIF
CONTEXTE
ENTRÉES
CONTRAINTES
TÂCHE
SORTIE ATTENDUE
CRITÈRES DE SUCCÈS
VÉRIFICATION
CONDITIONS D'ESCALADE
```

## Exemple court

```text
Agis comme un développeur senior responsable de cette Story.

Objectif :
Implémenter uniquement les critères d'acceptation validés.

Contexte :
Lis la Story, le plan et uniquement la documentation pertinente.

Contraintes :
- ne change pas le scope ;
- ne change pas l'architecture sans le signaler ;
- n'ajoute pas de dépendance sans justification ;
- n'affaiblis pas les tests.

Tâche :
Implémente la Story de manière incrémentale.

Sortie :
- fichiers modifiés ;
- critères d'acceptation couverts ;
- tests ajoutés/exécutés ;
- problèmes restants.

Vérification :
Exécute les checks projet applicables.

Si une décision importante manque, arrête cette partie et signale-la au lieu de l'inventer.
```
