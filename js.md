# Javascript


## Declaration de variables

### Var

### Let

### Const

### Déclaration multiple


## Les types en Javascript

Le type des données déterminent la nature des valeurs que vous allez manipuler au sein d'un programme.

## Les chaines de caractères

```js
let a = "Hello World"; // String
let b = 'Hello World'; // String
let c = `Hello icndsuivodsuvbuos World`; // String
```

## Les nombres

```js
let a = 123; // Number
let b = 123.456; // Number
```
## Les booléens

```js
let a = true;  // Booleen
let b = false; // Boolean
let c = 1===1; // Boolean
let d = 10 > 5; // Boolean
let e = 10 < 5; // Boolean
let f = 10 >= 5; // Boolean
```
on dit qu'une expression est booléene lorsque elle retourne une valeur de type "boolean"

## Vocabulaire

Une ligne de code est appelé --> une instruction.

## Les types primitifs et les types complexes

En JS les types primitifs sont les types de données qui ne stockent qu'une seule valeur. Les types primitifs sont les suivants:
- number 
- boolean
- string

```js
let a = 123; // Number
```

Les types complexes sont les types de données qui stockent des informations plus complexes. les types complexes sont les suivants:
- object (objet)
- array (tableau)
- function (fonction)

Pour les déclarer :
```js
let a = new <type>;
let b = {};
let c = [];
let d = function() {};
```

## Les Dates

```js
let a = new Date(); // Date
```
### Les méthodes de l'objet Date

```js
let a = new Date();
a.getDate(); // 1-31
```

## Les commentaires

Les commentaires sont des portions de code qui ne sont pas executées par le programme. Ils sont utilisés pour documenter le code.

# Les fonctions

Les fonctions sont des blocs de code qui peuvent etre appelés à partir d'autres parties du code dans le but d'executer une tache spécifique.

```js
function saySomething(message) {
    console.log(message);
}
```

On peut avoir 0, 1 ou plusieurs parametres dans une fontion.

```js
let hello = "Hello World"
saySomething(hello); // message
```
C'est un appel de fonction.

Nomenclature: Les fonctions sont nommées en camelCase.
Leur nom sera un verbe qui décrit l'action qu'elles effectuent.

## L'instruction return

```js
function add(a,b) {
    return a + b;
}

let nombre1, nombre2, resultat;

nombre1 = 10;
nombre2 = 20;

resultat = add(nombre1, nombre2);
```

# Les Events (évènements)

Les évènements sont des actions qui se produisent dans le navigateur. Les évènements sont déclanché par l'utilisateur ou par le navigateur lui-meme

