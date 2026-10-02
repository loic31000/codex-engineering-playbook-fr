# Bibliothèque de Prompts & Skills pour Codex

Bibliothèque personnelle et évolutive de **prompts, workflows, skills, checklists et références d’ingénierie logicielle**, pensée pour être utilisée dans **Obsidian** et versionnée sur **GitHub**.

Tout le repository est en **Markdown** et en **français**.

## Objectif

Le but n’est pas de collectionner des « prompts magiques ».

Le but est de construire progressivement une bibliothèque de **workflows d’ingénierie testés avec Codex** pour couvrir tout le cycle de développement :

```text
Idée
→ découverte
→ produit
→ spécification
→ architecture
→ UX/UI/design
→ sécurité
→ planification
→ implémentation
→ tests
→ review
→ convergence
→ PR
→ release
→ maintenance
```

## Utilisation dans Obsidian

Ouvre simplement la racine du repository comme Vault Obsidian.

Commence par :

- [[00-Accueil/00 - Commencer ici]]
- [[00-Accueil/01 - Workflow quotidien]]
- [[00-Accueil/03 - Choisir le bon prompt]]
- [[00-Accueil/04 - Index complet]]
- [[00-Accueil/05 - Cycle de vie des prompts]]
- [[00-Accueil/06 - Conventions de la bibliothèque]]

## Statuts

Chaque prompt peut évoluer selon quatre états :

```text
draft
  ↓
testing
  ↓
stable
  ↓
deprecated
```

### `draft`

Le prompt existe mais n’a pas encore été suffisamment éprouvé.

### `testing`

Le prompt est actuellement utilisé sur de vrais cas avec Codex.

### `stable`

Le prompt a produit des résultats satisfaisants sur plusieurs cas réels et ses limites sont comprises.

### `deprecated`

Le prompt est conservé pour historique mais ne devrait plus être utilisé.

## Règle de promotion vers `stable`

Un prompt ne devrait normalement devenir `stable` qu’après :

- au moins 3 utilisations réelles ;
- aucun problème critique connu ;
- une sortie suffisamment reproductible ;
- des instructions qui restent compréhensibles sans contexte caché ;
- une vérification qu’il ne pousse pas Codex à élargir silencieusement le scope.

## Structure

```text
00-Accueil/
01-Decouverte-Projet/
02-Produit-Scope/
03-Specifications-Epics-Stories/
04-Architecture-Stack/
05-Data-API-Integrations/
06-Frontend-Design-UX/
07-Securite-Privacy/
08-Planification-Taches/
09-Implementation/
10-Tests-Qualite/
11-Review-Convergence/
12-Git-PR-Release/
13-Debug-Maintenance/
14-Documentation/
15-Meta-Prompting/
16-Checklists-References/
```

Le frontend et le design disposent notamment de prompts dédiés pour :

- architecture frontend ;
- direction visuelle ;
- design system ;
- tokens ;
- écrans ;
- composants ;
- navigation ;
- responsive ;
- accessibilité ;
- formulaires ;
- états loading/empty/error ;
- UX writing ;
- motion ;
- Core Web Vitals ;
- visual QA ;
- dark mode ;
- review frontend finale.

## Philosophie

Un bon prompt de travail doit favoriser :

- objectif clair ;
- contexte pertinent ;
- scope explicite ;
- contraintes connues ;
- sortie attendue ;
- critères de succès ;
- vérification ;
- condition d’arrêt lorsqu’une décision importante manque.

La bibliothèque évite autant que possible :

- les méga-prompts ;
- le micro-management du raisonnement ;
- les décisions inventées par l’agent ;
- les critères vagues ;
- les prompts qui confondent génération de code et fin réelle de la tâche.

## Contribuer

Voir [[CONTRIBUTING]].

## Roadmap

Voir [[ROADMAP]].

## Licence

MIT — voir [[LICENSE]].
