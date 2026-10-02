# Sécurité de la bibliothèque

Cette bibliothèque contient des prompts susceptibles d’influencer la génération ou la review de code.

Un problème de sécurité peut donc concerner :

- un prompt qui recommande une pratique dangereuse ;
- un prompt qui demande des secrets ;
- un prompt qui encourage à contourner des contrôles ;
- une instruction qui affaiblit tests, auth ou autorisation ;
- une technique de prompt injection ajoutée involontairement ;
- un exemple qui expose des credentials ou données sensibles.

## Signaler un problème

Pour un repository personnel, crée une Issue privée ou corrige directement le fichier avant publication.

Pour un repository public avec plusieurs contributeurs, utilise les mécanismes privés de signalement de sécurité de la plateforme lorsque disponibles.

## Règles

Un prompt de cette bibliothèque ne devrait jamais demander :

- mot de passe réel ;
- token réel ;
- clé API réelle ;
- secret de production ;
- dump de données personnelles réelles.

Les exemples doivent utiliser des valeurs fictives.

## Review sécurité d’un prompt

Avant de promouvoir un prompt sécurité en `stable`, vérifier qu’il :

- distingue faits et hypothèses ;
- ne promet pas qu’un système est « sécurisé » sans preuve ;
- demande des vérifications déterministes ;
- traite l’autorisation côté serveur lorsque pertinent ;
- ne propose pas de désactiver un contrôle pour faire passer un test.
