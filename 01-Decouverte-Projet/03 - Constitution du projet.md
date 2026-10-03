---
titre: "Constitution du projet"
format: prompt
archetype: checklist
domaine: decouverte
tags:
  - governance
statut: draft
version: "0.2.0"
langue: fr-FR
outils:
  - codex
tests_reels: 0
cas_reussis: 0
modeles_testes: []
derniere_validation: null
derniere_revision: 2026-10-03
entrees_requises:
  - contexte-fourni
sortie_attendue: "constitution courte, exploitable et vérifiable"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Constitution du projet

## Quand l'utiliser

Quand tu veux définir les règles non négociables qui encadreront Codex et les développeurs.

## Prompt prêt à copier

```text
À partir du contexte du projet, rédige une constitution de développement courte et opérationnelle.

Elle doit définir les règles non négociables concernant :
- specification avant implémentation ;
- contrôle du scope ;
- architecture ;
- sécurité ;
- données et migrations ;
- dépendances ;
- tests ;
- documentation ;
- qualité ;
- Definition of Ready ;
- Definition of Done ;
- review ;
- merge.

Évite les règles vagues du type « faire du bon code ».

Chaque règle doit être :
- observable ;
- applicable ;
- vérifiable ;
- suffisamment concise.

Distingue :
- règle obligatoire ;
- recommandation ;
- décision nécessitant validation humaine.

Sortie : constitution courte, exploitable et vérifiable.

Si une information manquante change matériellement le résultat, marque-la « à clarifier » au lieu de l'inventer.
```

## Sortie attendue

Une constitution courte, exploitable et vérifiable.

## Points de contrôle

- [ ] Règles concrètes
- [ ] Pas de micro-management
- [ ] Différence obligatoire/recommandé
