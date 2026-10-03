---
titre: "Définir les exigences non fonctionnelles"
format: prompt
archetype: instruction
domaine: produit
tags:
  - nfr
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
sortie_attendue: "liste testable d'exigences non fonctionnelles"
niveau_risque: faible
actions_externes: false
donnees_sensibles: ne_pas_fournir
---

# Définir les exigences non fonctionnelles

## Quand l'utiliser

Avant l'architecture ou pour rendre des attentes vagues mesurables.

## Prompt prêt à copier

```text
Identifie les exigences non fonctionnelles pertinentes pour ce projet.

Examine :
- performance ;
- disponibilité ;
- scalabilité ;
- sécurité ;
- privacy ;
- accessibilité ;
- compatibilité ;
- maintenabilité ;
- observabilité ;
- résilience ;
- sauvegarde/restauration ;
- localisation ;
- conformité.

Pour chaque exigence :
- précise si elle est confirmée, hypothèse ou indécise ;
- transforme les formulations vagues en critères mesurables lorsque possible ;
- indique comment la vérifier.

N'invente pas de seuil si aucun objectif n'est connu.

Sortie : liste testable d'exigences non fonctionnelles.
```

## Sortie attendue

Une liste testable d'exigences non fonctionnelles.

## Points de contrôle

- [ ] Chaque exigence a une méthode de vérification
- [ ] Pas de chiffres inventés
