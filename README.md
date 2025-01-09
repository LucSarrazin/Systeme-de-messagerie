# Systeme-de-Messagerie

## Description

Ce dépôt contient le code source d'un **système de messagerie**, permettant d'envoyer, recevoir et gérer des messages entre utilisateurs. Ce projet a été conçu pour mettre en pratique des compétences en développement web backend et en gestion de bases de données.

## Fonctionnalités

- **Inscription et connexion utilisateur** : Système sécurisé d'authentification.
- **Envoi de messages** : Les utilisateurs peuvent envoyer des messages privés.
- **Boîte de réception et d'envoi** : Vue des messages reçus.
- **Sécurité** : Les mots de passe sont chiffrés et les données sensibles protégées.

## Technologies utilisées

- **HTML / CSS** : Interface utilisateur et design.
- **PHP** : Backend et gestion des fonctionnalités serveur.
- **MySQL** : Gestion de la base de données pour stocker les utilisateurs et les messages.
- **JavaScript** : Amélioration de l'interactivité et validation des formulaires.

## Prérequis

Avant d'installer le projet, assurez-vous d'avoir :
- Un serveur local (comme **XAMPP**, **WAMP**, ou **MAMP**).
- **PHP** (version 7.4 ou ultérieure).
- **MySQL** (base de données).
- Un navigateur moderne.

## Installation

1. Clonez ce dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/LucSarrazin/Systeme-de-messagerie.git
   ```

2. Déplacez-vous dans le répertoire du projet :
   ```bash
   cd Systeme-de-messagerie
   ```

3. Configurez la base de données :
   - Importez le fichier `mydata.sql` dans votre gestionnaire de base de données (ex. phpMyAdmin).
   - Modifiez le fichier `config.php` pour y ajouter vos informations de connexion MySQL.

4. Lancez un serveur local et accédez au projet via l'URL locale (ex. `http://localhost/Systeme-de-messagerie`).

## Aperçu

Ce système de messagerie offre une interface intuitive pour gérer vos communications. Le projet se concentre sur une expérience utilisateur simple et efficace.

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez proposer des améliorations ou corriger des bugs :
- Forkez le projet.
- Créez une branche pour votre fonctionnalité/correction :
   ```bash
   git checkout -b feature/ma-fonctionnalite
   ```
- Faites vos modifications et committez-les :
   ```bash
   git commit -m "Ajout d'une fonctionnalité"
   ```
- Envoyez une pull request.

## Contact

Ce projet est un projet scolaire personnel. Il est destiné à des fins éducatives et ne doit pas être utilisé à des fins commerciales.
