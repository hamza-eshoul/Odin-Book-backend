## Backend du Projet Odin Book

[![en](https://img.shields.io/badge/lang-en-red)](README.md)

Ce dépôt comprend la partie backend du Full Stack Odin Book projet créé pour [Odin Project](https://www.theodinproject.com/lessons/nodejs-odin-book).

L'objectif du projet est de créer un clone de la plateforme de médias sociaux Facebook en implémentant les principales fonctionnalités de la plateforme, à savoir les utilisateurs, les profils, les publications, les « likes », les « amis » ainsi que le fil d'actualité.

- Lien du projet - https://odin-book-project.onrender.com/
- Dépôt principal du projet - https://github.com/skynter/Odin-Book-frontend
- Dépôt frontend du projet - https://github.com/hamza-eshoul/Odin-Book-frontend

## Technologies Utilisées

- NodeJS
- ExpressJS
- MongoDB
- Cloudinary NodeJS

## Principales Fonctionnalités

- Authentification à travers les JWTs
- Personnalisation des profils d'utilisateurs
- Opérations CRUD pour la fonctionnalité "amis" (Ajout d'amis / Suppression d'amis / Gestion des demandes d'amis)
- Opérations CRUD pour la fonctionnalité "publications" (Ajout de publications / Suppression de publications )
- Opérations CRUD pour la fonctionnalité "commentaires" (Ajout de commentaires / Modifiation de commentaires / Suppression de commentaires)
## Installation

Pour exécuter le projet localement sur votre machine :

- Exécutez la commande suivante pour générer un serveur local de développement :
```
npm run dev
```

- Accédez au dépôt frontend du projet et générez un serveur local de développement pour interagir avec l'API


- Les points de terminaison de l'API figurant au niveau de ce dépôt sont accessibles à travers l'API hébergé sur https://odin-book-api-g5zs.onrender.com

- Les deux points de terminaisons principaux de l'API sont le POST https://odin-book-api-g5zs.onrender.com/posts et le POST https://odin-book-api-g5zs.onrender.com/users/:user_id/send_friend_request
