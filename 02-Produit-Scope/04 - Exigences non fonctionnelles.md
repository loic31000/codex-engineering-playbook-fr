---
titre: "Définir les exigences non fonctionnelles"
type: prompt
tags:
  - nfr
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
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
```

## Sortie attendue

Une liste testable d'exigences non fonctionnelles.

## Points de contrôle

- [ ] Chaque exigence a une méthode de vérification
- [ ] Pas de chiffres inventés
