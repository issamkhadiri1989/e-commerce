# Etape 4

Cette étape consiste à assurer la sécurité de votre site e‑commerce. Pour cela, vous êtes invités à créer un formulaire d’inscription ainsi qu’un formulaire de connexion.

Ce TP sera divisé en plusieurs étapes. Chaque étape sera développée séparément.

Les étapes sont les suivantes :

1. Créer un formulaire d’inscription. [Réaliser](#formulaire-dinscription)

2. Créer un formulaire de connexion. [Réaliser](#formulaire-dinscription)

3. Sécuriser la page profil déjà développée à l’étape 1 _(en cours...)_

## Formulaire d'inscription: 

En vous basant sur l’exemple vu en cours, vous devez dynamiser le formulaire d’inscription.

Vous devez utiliser :

- RepeatedType pour la confirmation du mot de passe


- PasswordType pour le champ mot de passe

- Les mots de passe doivent être hachés avant d’être enregistrés en base de données

- Le code doit respecter les principes SOLID (en favorisant l’utilisation des services)

## Formulaire de connexion : 

Comme vu en cours, vous devez mettre en place le système de connexion via *form_login*.

- Connecter vos utilisateurs

- Afficher « Bienvenue, XXXX » lorsque l’utilisateur est connecté, ainsi qu’un lien de déconnexion

- Ajouter un lien de connexion pour les utilisateurs non connectés