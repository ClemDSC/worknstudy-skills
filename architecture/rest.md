# REST API

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les verbes HTTP  ✔️
=> Les principaux verbes sont GET / POST / PUT / DELETE. Ils permettent de définir l'action de la requête.

- les statuts HTTP  ✔️
=> Les status sont représentés par des codes, et envoyé dans les réponses des requêtes. 
Chaque "famille" de code a un sens spécifique :
Informationnels : 100-199
Succes : 200-299
Redirection : 300-399
Erreur client : 400-499
Erreur Serveur : 500-599 

- les endpoints  ✔️ 
=> Ce sont les points d'entrée / les URLs, qui permettent d'accéder aux données de l'api.

- CORS  ✔️
Il s'agit d'un système permettant le partage de ressources entre différentes origines. Pour autoriser ce partage, on peut soit ajouter une spécification dans le header des requêtes http, ou encore les autoriser depuis le code comme ici : 
```javascript
app.use(
  cors({
    origin: process.env.FRONTEND_URL ?? "http://localhost:3000",
    optionsSuccessStatus: 200,
    credentials: true,
  })
);
```

- la nomenclature recommandée pour les routes  ✔️
=> Les routes ont généralement la nomenclature suivante :
- la constante correspondante à l'application (App ou router si fichier de route)
- le verbe HTTP
- le chemin d'accès (définition de la route)
- la méthode du controleur associé à la requête

## 💻 J'utilise

### Un exemple personnel commenté  ✔️

```javascript
router.post("/masterclass", multer, masterclassController.addOne);
router.get("/masterclass", masterclassController.getAll);
router.get("/masterclass/:id", masterclassController.getOne);
router.put("/masterclass/:id", masterclassController.editOne);
router.delete("/masterclass/:id", masterclassController.deleteOne);
```

### Utilisation dans un projet  ✔️

[Masterwild - Ficher Routes](https://github.com/ClemDSC/masterwild/blob/main/backend/src/routes/adminRoutes.js)

Description : ce fichier contient les routes permettant de gérer une api de masterclasses.

### Utilisation en production si applicable ❌ 

### Utilisation en environement professionnel ❌ 

Description :

## 🌐 J'utilise des ressources

### List of HTTP status codes

[Wikipedia](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)

- Ressource permettant de définir au mieux les statuts envoyés dans les réponses des requêtes http

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
