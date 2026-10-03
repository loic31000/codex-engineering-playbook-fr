# Bibliothèque de Prompts & Skills pour Codex

<p align="center">
  <a href="https://github.com/loic31000/codex-engineering-playbook-fr/tree/main">
    <img src="https://img.shields.io/badge/Fran%C3%A7ais-main-0055A4?style=for-the-badge" alt="Français - main">
  </a>
  <a href="https://github.com/loic31000/codex-engineering-playbook-fr/tree/en">
    <img src="https://img.shields.io/badge/English-en-012169?style=for-the-badge" alt="English - en">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Codex-OpenAI-000000?style=for-the-badge&logo=openai&logoColor=white" alt="Codex / OpenAI">
  <img src="https://img.shields.io/badge/Markdown-100%25-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
  <img src="https://img.shields.io/badge/Obsidian-Vault-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white" alt="Obsidian">
  <img src="https://img.shields.io/badge/GitHub-Versioned-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge" alt="MIT License">
</p>

> 🇫🇷 **Version française — branche `main`**  
> 🇬🇧 La version anglaise complète est disponible sur la branche **[`en`](https://github.com/loic31000/codex-engineering-playbook-fr/tree/en)**.

Bibliothèque personnelle et évolutive de **prompts, workflows, skills, checklists et références d’ingénierie logicielle**, pensée pour être utilisée dans **Obsidian** et versionnée sur **GitHub**.

Le dépôt est maintenu en deux versions :
- **FR** : `main` — source de vérité ;
- **EN** : `en` — miroir anglais synchronisé avec la version française.

La bibliothèque est entièrement en **Markdown**.

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


## Évolution V0.2 — audit octobre 2026

La V0.2 applique les recommandations de l'audit approfondi de la bibliothèque :

- contrat de sortie intégré dans le bloc copiable ;
- métadonnées séparant `format` et `archetype` ;
- entrées, niveau de risque et historique de validation structurés ;
- conditions d'incertitude renforcées sans transformer les fiches en méga-prompts ;
- sécurité agentique et prompt injection ;
- frontend enrichi : références visuelles, i18n/RTL et boucle screenshot → comparaison → correction ;
- WCAG : séparation conformité / non vérifiable / bonne pratique ;
- protocole de tests réels et revalidation des prompts `stable` ;
- glossaire technique français/anglais.

Les prompts restent `draft` tant qu'ils n'ont pas accumulé de preuves d'usage réel. La révision structurelle ne vaut pas validation empirique.
