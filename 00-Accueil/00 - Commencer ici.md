# Commencer ici

Cette bibliothèque est pensée comme un **vault Obsidian personnel de prompts et de skills** pour travailler avec Codex.

Elle ne contient :

- aucun script ;
- aucune automatisation ;
- aucun fichier de configuration ;
- aucun code exécutable.

Elle contient uniquement des fichiers Markdown `.md`.

## Comment l'utiliser

Pour une tâche importante, évite le prompt unique qui fait tout.

Utilise plutôt ce cycle :

```text
1. Clarifier
2. Spécifier
3. Planifier
4. Implémenter
5. Tester
6. Relire
7. Converger
8. Préparer la PR
```

Pour le frontend :

```text
1. UX / parcours
2. Direction visuelle
3. Design system / tokens
4. Structure des écrans
5. Architecture composants
6. Responsive
7. Accessibilité
8. Performance
9. Visual QA
```

## Règles importantes

- Ne demande pas à Codex d'inventer une décision métier inconnue.
- Utilise les états : `confirmé`, `hypothèse`, `indécis`, `N/A`.
- Pour une grosse tâche, demande d'abord un plan.
- Une implémentation n'est pas terminée tant que les critères d'acceptation et les tests ne passent pas.
- Les changements d'architecture, de sécurité, de persistance ou de contrat public doivent être explicités.
- Les coûts financiers ne font pas partie des User Stories.

Voir aussi :

- [[01 - Workflow quotidien]]
- [[02 - Formule de prompt de référence]]
- [[03 - Choisir le bon prompt]]
