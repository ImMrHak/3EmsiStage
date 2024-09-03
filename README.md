# CarFleet-Management

CarFleet-Management est une application complète de gestion de flotte de véhicules, comprenant un backend développé en Spring Boot, un frontend développé en React, et une application mobile Android permettant de suivre les voitures en temps réel.

## Description

CarFleet-Management offre des fonctionnalités pour :
- **Gérer les voitures** : Ajout, modification et suppression de véhicules.
- **Suivi des emplacements en temps réel** : Utilisation de l'application Android installée dans les voitures pour suivre leur position.
- **Historique des déplacements** : Conserver un enregistrement des déplacements des véhicules.
- **Gestion des utilisateurs** : Gestion des informations personnelles et des rôles des utilisateurs.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants :

- **Java JDK 8 ou supérieur**
- **Maven**
- **Node.js**
- **Android Studio** (pour l'application mobile)
- **Une base de données (SQL Server, MySQL, PostgreSQL, etc.)**

## Installation

### Backend

1. **Clonez** ce dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/votre-utilisateur/CarFleet-Management.git
Importez le projet Spring Boot dans votre IDE préféré (Eclipse, IntelliJ, etc.).

Configurez les informations de la base de données dans le fichier application.properties.

Compilez et exécutez l'application backend avec Maven :

bash
Copier le code
mvn clean install
mvn spring-boot:run
Frontend
Accédez au répertoire frontend :

bash
Copier le code
cd frontend
Installez les dépendances nécessaires :

bash
Copier le code
npm install
Lancez l'application frontend :

bash
Copier le code
npm start
Application Android
Ouvrez le répertoire android-app dans Android Studio.

Compilez et installez l'application sur un appareil Android (ou un émulateur) qui sera installé dans les véhicules :

Pour compiler, cliquez sur "Build" dans Android Studio.
Pour installer sur un appareil, connectez-le et cliquez sur "Run".
Lancez l'application Android sur le dispositif. Elle commencera à envoyer les données de localisation en temps réel au backend.

Utilisation
Lancez le backend et le frontend.

Ouvrez l'interface utilisateur dans votre navigateur Web en accédant à http://localhost:3000.

Connectez-vous pour accéder aux fonctionnalités de gestion des voitures, de suivi des emplacements, et de gestion des utilisateurs.

Installez et lancez l'application Android sur les véhicules pour commencer le suivi en temps réel.

Contribuer
Les contributions sont les bienvenues ! Pour contribuer à CarFleet-Management, veuillez suivre les étapes suivantes :

Fork ce dépôt.
Créez une branche pour votre fonctionnalité :
bash
Copier le code
git checkout -b feature/NouvelleFonctionnalité
Committez vos changements :
bash
Copier le code
git commit -am 'Ajouter une nouvelle fonctionnalité'
Push votre branche sur le dépôt distant :
bash
Copier le code
git push origin feature/NouvelleFonctionnalité
Créez une nouvelle Pull Request.
Auteurs
Mohamed Hakkou
Yahya Zini
