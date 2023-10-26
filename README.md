## Odin Book Project Backend

[![fr](https://img.shields.io/badge/lang-fr-blue)](README.fr.md)

This is the backend repository for the Full Stack Odin Book Final Project built for the [Odin Project Curriculum](https://www.theodinproject.com/lessons/nodejs-odin-book).

The goal of the project was to build a clone of the social media platform Facebook implementing the core features of the platform, namely users, profiles, posts, "liking", "friending" and the news feed.

- Project's Live Preview url - https://odin-book-project.onrender.com/
- Project's Parent Repository - https://github.com/hamza-eshoul/Messaging-App
- Project's Frontend Repository - https://github.com/hamza-eshoul/Odin-Book-frontend

## Technologies Used

- NodeJS
- ExpressJS
- MongoDB
- Cloudinary NodeJS

## Key features

- Persistent Authentication using JWTs
- Customizing users profiles
- Friends CRUD operations (Adding Friends / Deleting Friends / Accepting Friend Requests / Rejecting Friend Requests)
- Posts CRUD operations (Adding Posts / Deleting Posts)
- Posts Comments CRUD operations (Adding Comments / Updating Comments / Deleting Comments)

## Installation

To run the project locally :

- Run the following command to spin up a local development server :

```
npm run dev
```

- Run the following command to spin up a local development server

```
npm start
```

- Access the frontend repository of the project and spin up a local development server to interact with the API

- The API endpoints can be accessed through the hosted version of the API on https://odin-book-api-g5zs.onrender.com

- The two main API endpoints are the POST https://odin-book-api-g5zs.onrender.com/posts endpoint and the POST https://odin-book-api-g5zs.onrender.com/users/:user_id/send_friend_request
