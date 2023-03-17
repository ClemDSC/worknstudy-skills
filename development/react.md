# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
  Utilisé avec le hook "useState()", cela permet de garder la valeur d'une variable entre deux appels de fonctions.
  Format :

```javascript
const [maVariable, setMaVariable] = useState();
```

- les composants enfants et les _props_ qu'on leur passe ✔️
  React se divise en plusieurs composants et sous-composants (on parle de relation parent / enfant).
  Le passage de props (de parent à enfant) permet de récupérer des données (variables, fonctions, etc...) afin de les réutiliser dans le composant enfant sans avoir besoin de les redéfinir.

- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
  Des fonctions peuvent être déclenchées par action de l'utilisateur. On parle alors d'évènement (click sur un bouton, écriture dans un champ de formulaire, validation de formulaire...)

- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
  React propose le hook "useEffect" qui permet un rechargement du composant (et donc des données contenues dans la page).
  Si le tableau de dépendance est vide, ce qui est contenu dans la fonction sera exécuté une fois au montage du composant (au premier chargement)
  Si le tableau de dépendance contient une variable ce qui est contenu dans la fonction sera exécuté à chaque mofification de cette variable.
  Si un return est spécifié, il sera exécuté en démontage du composant.

- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ✔️
  Ce hook, similaire dans le principe à useState, permet de gérer dans une variable unique plusieurs mutations. 

- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext`✔️
  Permet de rendre du contenu accessible n'importe où dans l'application, sans ce soucier des relations parent/enfant des composants. 

## 💻 J'utilise

### Un exemple personnel commenté  ✔️

```javascript
  // check id
  const { wilderId } = useParams();

  // get wilders
  const [wilder, setWilder] = useState();
  useEffect(() => {
    axios.get(`${process.env.REACT_APP_BACK_URL}/wilder/${wilderId}`).then((res) => {
      setWilder(res.data);
      console.log(res.data);
    });
  }, [wilderId]);
  ```

### Utilisation dans un projet  ✔️

[Github - TeamLions x NASA](https://github.com/ClemDSC/P2-TeamLions-X-NASA)

But de l'application : consommer une API et proposer une application utilisant les données récoltées.

### Utilisation en production si applicable  ✔️

[Portfolio](https://clemencepham-portfolio.web.app/)

Description : utilisation de React pour créer facilement et rapidement un portfolio.

### Utilisation en environement professionnel ❌ 

Description :

## 🌐 J'utilise des ressources

### Newsletter React Hebdo

- [Newsletter](https://thisweekinreact.com/fr/newsletter)
- Description : Articles proposés par Sébastien Lorber, expert React.

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
