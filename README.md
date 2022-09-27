# Notre 1er test de NodeJS

## Exercice

Nous allons tester un package node qui nous permettra de vérifier si notre structure HTML est correcte.

## Correction

Nous allons installer le package npm "w3c-html-validator",

````shell
# i = install
npm i w3c-html-validator
````

Ensuite, si je lis la [documentation](https://github.com/center-key/w3c-html-validator)

Il est dit que je dois créer un script dans le package.json

````js
"scripts": {
    "validate": "html-validator ./*.html",
    "all": "html-validator --quiet"
},
````
Ensuite, j'ai plus qu'à lancer la commande

````shell
npm run validate
````

Et dans mon terminal, je vais voir si j'ai des erreurs ou non.
