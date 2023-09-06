# P7 - Mon Vieux Grimoire

Project 7 OpenClassrooms

![Notation de livres](https://img.shields.io/badge/Notation%20de%20livres-Mon_vieux_grimoire-gold)

<div align="center">
<img src="https://github.com/JonathanCornic/mon-vieux-grimoire/blob/main/mon-vieux-grimoire-preview.png">
</div>

## Création du Backend

- Création d'un serveur express simple.
- Création d'une **API RESTful**.
- Configuration des models **Book** et **User**.
- Création du **CRUD** ains que configuration du **router**.
- Mise en plase d'un système d'authentification par **Token**(jwt).
- Hachage du mot de passe avec **bcrypt**.
- Mise en place d'une gestion des fichiers utilisateur via **Sharp** et **Multer**.
- Ajout et calcul de la notation des livres.

## Technologies utilisées

- Node Js
- Express
- MongoDB
- Git

## Comment lancer projet ?

Projet testé sur node 19.

Ouvrez un terminal puis `git clone https://github.com/7S-Coder/P7.git`

## Créez un fichier .env à la racine du projet avec en parametres

- **VITE_API_KEY**: Adresse de votre base de donnée mongoDB
- **VITE_TOKEN_SECRET**: Votre clé secrète
- **VITE_SERVER_PORT**: votre port d'écoute

## Lancer le frontend

Ouvrez un terminal puis `cd frontend`, faites la commande `npm install` pour installer les dépendances puis `npm start` pour lancer le client.

## Lancer le backend

Ouvrez un terminal puis `cd backend`, faites la commande `npm install` pour installer les dépendances puis `nodemon` pour lancer le server.
