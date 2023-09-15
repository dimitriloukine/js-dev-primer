# Les trucs à installer

## VSCode

C'est ton éditeur de code, absolument tout le monde utilise l'utilise. VSCode veut dire Visual Studio Code, et c'est un **éditeur de code** mais il ne faut pas le confondre avec Visual Studio qui est un IDE. 

## NVM - Node Version Manager
NVM (for windows) c'est un truc qui permet d'installer plusieurs versions de Node différentes. Là comme ça t'en as pas besoin, mais c'est juste beaucoup trop chiant d'installer NVM si t'as déjà installé NodeJS (j'ai perdu 1h auj exactement à cause de ça).

## NodeJS
NVM va l'installer pour toi. NodeJS est un environnement d'execution pour du JS, ça permet d'executer du JS ailleur que dans ton navigateur.

## NPM - Node Package Manager
NPM est un gestionnaire de paquets pour node, un peu comme Apt sur linux.

## Git 
git est un système de contrôle de version de ton code, ça permet de tracer tous les changements dans ton code dans le temps, revenir en arrière, bosser sur plusieurs versions en parallèle, savoir qui a fait de la merde quand, bosser à plusieurs, y compris sur le même fichier etc. Y'en avait d'autres avant git, mais git a plié le game. C'est fait par le mec qui a fait Linux BTW.

Tu peux te créer un compte sur github dans la foulée, c'est gratos et ils vont héberger tout ton code. Git



# NodeJS

Tu peux faire pas mal de trucs sans avoir besoin d'utiliser quoi que ce soit d'autre, tu code, tu run le code, tu vois si ça marche.

## Hello World

Ben faut faire que ton code écrive 'Hello World'.

## Fizz Buzz

Players generally sit in a circle. The player designated to go first says the number "1", and the players then count upwards in turn. However, any number divisible by three is replaced by the word fizz and any number divisible by five by the word buzz. Numbers divisible by both three and five (i.e. divisible by 15) become fizz buzz. A player who hesitates or makes a mistake is eliminated.

For example, a typical round of fizz buzz would start as follows:

1, 2, 'Fizz', 4, 'Buzz', 'Fizz', 7, 8, 'Fizz', 'Buzz', 11, 'Fizz', 13, 14, 'FizzBuzz', 16, 17, 'Fizz', 19, 'Buzz', 'Fizz', 22, 23, 'Fizz', 'Buzz', 26, 'Fizz', 28, 29, 'FizzBuzz', 31, 32, 'Fizz', 34, 'Buzz', 'Fizz', ...

## Suite de Fibonnacci

In mathematics, the Fibonacci sequence is a sequence in which each number is the sum of the two preceding ones. Numbers that are part of the Fibonacci sequence are known as Fibonacci numbers. The sequence commonly starts from 0 and 1, although some authors start the sequence from 1 and 1 or sometimes (as did Fibonacci) from 1 and 2. Starting from 0 and 1, the first few values in the sequence are:[1]

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144...

## Trouver un truc OOP à faire



## Typescript

Au delà de savoir faire des trucs qui impliquent des algos, dans la vraie vie, les devs JavaScript n'écrivent pas de JavaScript, ils écrivent du dans un autre language, TypeScript, qui est un superset de JS (tout code JavaScript est du TypeScript valide, mais pas l'inverse ). La principale différence est que TypeScript est un language fortement typé, contrairement à JavaScript.

En javascript 1 et "1", sont deux choses différentes. 1 est un nombre, "1" est une chaine de caractères qui ne contient un seul caractère. JavaScript va essayer de se démerder à transformer les types de ses variables en fonction de ce que tu fais, mais les résultats sont hasardeux:

L'opérateur + est un opérateur d'addition pour les nombres et un opérateur de concaténation pour les chaines de caractères, mais JS fait typiquement n'imp avec.

 1  + 1 = 2;
"1" + 1 = "11";
"1" - 1 = 0;

TypeScript ne va juste pas te laisser additionner une chaine de caractère et un nombre, et de manière plus poussée, tu vas avoir un type que tu va définir pour toutes tes variables, tes classes etc. et Typescript va faire que tu vas devoir t'y tenir. 

Tu ne peux pas encore apprécier la valeur ajoutée de truc mais je t'assure que c'est putain de merveilleux. 


# Les trucs de database

Tu ne vas pas y couper, mais j'y connais que dalle.

## SQL

C'est chiant mais c'est sur que tu l'auras dans ta formation ou que ce soit.

## MongoDB

T'as d'au


# Frontend 

## HTML + CSS

HTML c'est trivial, c'est juste du markup.

Le CSS en vrai c'est assez dur pour faire des trucs plus avancés. Maintenant t'as des trucs comme flexbox qui te facilitent la vie, mais des fois ça fait pas ce que tu veux et c'est chaud de savoir pourquoi.

## SCSS

Le CSS c'est de la merde à écrire mais t'as des languagues qui se compilent en CSS et permettent de faire la même chose plus facilement. le plus courrant, c'est SCSS, il existe aussi SASS, LessCSS, et JSS (CSS-in-JS) mais tu t'en branles.


## Les libs et les frameworks.

En pratique, si tu fais du front, tu ne vas bosser sur des trucs compliqués ou y'a mille manière de se gauffrer. 



### React + Next

La on rentre dans le vrai game. Tu sais faire du react, t'as du taf direct. Mais on verra plus tard ce que ça fait.

### Angular

Et si tu vas vraiment bosser sur des trucs complexes, Angular c'est l'artillerie lourde. Dans ma boite c'est ils aiment vachement Angular mais t'as quand même 2 fois moins de devs Angular que React à cause de la complexité.



### jQuery

Bon, c'est plus du tout une techno d'actu, mais en réalité, si tu n'utilises pas un des frameworks sous-nommés, c'est que tu bosses sur un truc qui date de mathuz' et qui utilise jQuery. jQuery, c'est une lib qui date d'une époque ou tous les navigateurs se disaient merde les uns aux autres et ça te propose une API qui marche pour tout.



# Trucs à Apprendre à utiliser ou à faire

- Apprendre à écrire du markdown, juste parce que c'est trop pratique pour noter des trucs et c'est un bon prétexte pour ...
- Apprendre Git
- Edition multiline dans ton éditeur de code
- Utiliser Bash, que tu sais sans doute déjà utiliser