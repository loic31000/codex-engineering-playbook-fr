---
titre: "Détecter architecture drift"
type: prompt
tags:
  - review
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Détecter architecture drift

## Quand l'utiliser

Pour vérifier qu'une feature n'érode pas les frontières.

## Prompt prêt à copier

```text
Compare ce changement à l'architecture documentée.

Cherche :
- dépendance inversée ;
- accès direct interdit ;
- logique métier dans mauvaise couche ;
- duplication de concepts ;
- dépendance circulaire ;
- nouvelle abstraction non documentée ;
- persistance traversant une frontière ;
- contournement d'API interne.

Classe :
- drift bloquant ;
- dette acceptable ;
- faux positif.
```

## Sortie attendue

Une review priorisée et actionnable.
