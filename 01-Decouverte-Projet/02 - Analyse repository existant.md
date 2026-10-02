---
titre: "Analyse repository existant"
type: prompt
tags:
  - brownfield
  - repo-analysis
statut: draft
version: "0.1.0"
langue: fr
outils:
  - codex
test_reel: false
---

# Analyse repository existant

## Quand l'utiliser

Quand tu reprends un codebase existant et veux comprendre sa structure avant de le modifier.

## Prompt prêt à copier

```text
Analyse ce repository comme un développeur senior qui doit le reprendre sans casser son comportement.

Ne modifie rien.

Identifie :
- langage(s) et frameworks ;
- structure du repository ;
- applications/packages ;
- points d'entrée ;
- architecture réelle ;
- modules et responsabilités ;
- dépendances importantes ;
- base de données et migrations ;
- API/contrats ;
- authentification/autorisation ;
- tests ;
- CI/CD ;
- configuration/environnements ;
- observabilité ;
- dette technique visible ;
- zones sensibles sécurité ;
- documentation existante ;
- incohérences entre documentation et code.

Sépare clairement :
- faits observés ;
- hypothèses ;
- zones inconnues ;
- risques.

Termine par une carte du repository et une liste des 10 fichiers/dossiers à comprendre en priorité.
```

## Sortie attendue

Une cartographie fiable du codebase et de ses risques.

## Points de contrôle

- [ ] Pas de modifications
- [ ] Faits séparés des hypothèses
- [ ] Architecture réelle décrite, pas seulement supposée
