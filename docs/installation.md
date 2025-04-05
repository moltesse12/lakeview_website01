# Installation

## Prérequis

Avant de commencer, vous devez avoir les éléments suivants installés sur votre machine :
- **Node.js** : Version >= 14.x
- **npm** ou **yarn** : Gestionnaire de paquets pour JavaScript
- **Git** : Outil de gestion de version

## Étapes d'installation

1. Clonez ce dépôt :
    ```bash
    git clone https://github.com/ton-nom-utilisateur/lakeview_website01.git
    ```

2. Accédez au dossier du projet :
    ```bash
    cd lakeview_website01
    ```

3. Installez les dépendances pour le frontend :
    ```bash
    cd Client
    npm install
    ```

4. Installez les dépendances pour le backend :
    ```bash
    cd ../Server
    npm install
    ```

## Lancer le projet

1. Lancez le serveur backend :
    ```bash
    cd Server
    node src/server.js
    ```

2. Lancez le frontend :
    ```bash
    cd ../Client
    npm start
    ```

Cela ouvrira le projet dans votre navigateur à l'adresse `http://localhost:3000`.
