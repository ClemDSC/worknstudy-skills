# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ❌  ✔️
=> L'utilisation des types permet de controller le code, par exemple, de manière à recevoir ce qui est attendu au retour d'une fonction ou dans un de ses arguments. 
Si nous avons besoin de manipuler un nombre en paramètre, nous ne voudrions pas recevoir une chaîne de caractère.
Le fait de typer ce paramètre en "number" évitera les erreurs.

- les types de bases  ✔️
boolean, number, string, enum, any, void, null...

- comment et pourquoi étendre une interface  ✔️
```javascript
interface Voiture extends Vehicle{
...}
```
Étendre une interface permet d'utiliser ses propriétés et d'en ajouter d'autres spécifiques.

- les classes et les decorators  ✔️
Les classes permettent de modéliser des objets, et avec typescript, nous les utilisons notamment pour en faire des types.
Les décorateurs TypeScript sont des annotations permettant de contenir une fonction, puis d’altérer du code au moment de sa déclaration/utilisation. 
## 💻 J'utilise

### Un exemple personnel commenté  ✔️
Dans un projet Angular, utilisation du décorateur @Input() permettant de transmettre des props à son composant enfant : 

```typescript
// On initialise notre propriété avec une valeur par défaut
// On décore notre propriété avec @Input()
 @Input() myInputData: string = "" 
```

### Utilisation dans un projet  ✔️

[Playerbook](https://github.com/ClemDSC/playerbook)

Description : Plateforme sociale permettant la mise en relation des joueurs de jeux-vidéos (application Angular)

### Utilisation en production si applicable ❌ 

### Utilisation en environement professionnel ❌ 

## 🌐 J'utilise des ressources

### Titre

- lien
- description

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
