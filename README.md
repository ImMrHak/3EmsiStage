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
2. **Importez** le projet Spring Boot dans votre IDE préféré (Eclipse, IntelliJ, etc.).
3. **Configurez** les informations de la base de données dans le fichier `application.properties`.
4. **Compilez** et **exécutez** l'application backend avec Maven :

   ```bash
   mvn clean install
   ```

   ```bash
   mvn spring-boot:run
   ```

### Frontend

2. **Accédez** au répertoire frontend :
   ```bash
   cd frontend
    ```
3.  **Installez** les dépendances nécessaires :
   ```bash
   npm install
   ```
4.  **Lancez** l'application frontend :
   ```bash
   npm start
   ```

### Application Android

1. **Ouvrez** le répertoire `android-app` dans Android Studio.
2. **Compilez** et **installez** l'application sur un appareil Android (ou un émulateur) qui sera installé dans les véhicules :
- Pour compiler, cliquez sur "Build" dans Android Studio.
- Pour installer sur un appareil, connectez-le et cliquez sur "Run".
3. **Lancez** l'application Android sur le dispositif. Elle commencera à envoyer les données de localisation en temps réel au backend.

## Utilisation

1. **Lancez** le backend et le frontend.
2. **Ouvrez** l'interface utilisateur dans votre navigateur Web en accédant à [http://localhost:3000](http://localhost:3000).
3. **Connectez-vous** pour accéder aux fonctionnalités de gestion des voitures, de suivi des emplacements, et de gestion des utilisateurs.
4. **Installez** et **lancez** l'application Android sur les véhicules pour commencer le suivi en temps réel.

## Contribuer

Les contributions sont les bienvenues ! Pour contribuer à CarFleet-Management, veuillez suivre les étapes suivantes :

1. **Fork** ce dépôt.
2. **Créez** une branche pour votre fonctionnalité :
   ```bash
   git checkout -b feature/NouvelleFonctionnalité
   ```
   
3. **Committez** vos changements :

   ```bash
   git commit -am 'Ajouter une nouvelle fonctionnalité'
   ```
   
4. **Push** votre branche sur le dépôt distant :

   ```bash
   git push origin feature/NouvelleFonctionnalité
   ```
5. **Créez** une nouvelle Pull Request.

## Auteurs

- Mohamed Hakkou
- Yahya Zini

