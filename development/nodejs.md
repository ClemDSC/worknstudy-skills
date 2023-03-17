# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple)  ✔️ => Ce type de système maintient le fonctionnement du serveur et permet la mise à jour instantannée dès qu'une modification sur un fichier est enregistrée (hot reload)
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple)  ✔️ => La connexion se fait par le biais de variables d'environnement en lien avec la base de données selectionnée .
  Exemple avec l'ORM Prisma et mySql :

```javascript
DATABASE_URL =
  "mysql://username:password@localhost:3306/dbscheme?schema=public";
```
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ❌ 
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌ 

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```javascript
const express = require("express");
const app = express();

// Serve the public folder for public resources
app.use(express.static(path.join(__dirname, "../public")));

// API routes
const router = express.Router();

const adminRoutes = require("./routes/adminRoutes");
const userRoutes = require("./routes/userRoutes");
```

### Utilisation dans un projet ❌ / ✔️

[Github - Masterwild](https://github.com/ClemDSC/TeamKarma-P3-Masterwild/tree/main/backend)

Description : back-end développé avec le framework Express.

### Utilisation en production si applicable❌ 

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ 

Description :

## 🌐 J'utilise des ressources

### List of HTTP status codes

[Wikipedia](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)

- Ressource permettant de définir au mieux les statuts envoyés dans les réponses des requêteshttp

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
