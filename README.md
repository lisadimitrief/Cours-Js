# <div align="center">Cours de Javascript</div>  
## Introduction au JavaScript  
# <div align="center"> ![JavaScript](img/js.png)</div>  
__Le JavaScript__ est un langage de programmation de scripts principalement employé dans les pages web interactives et à ce titre est une partie essentielle des applications web. Avec les langages HTML et CSS, JavaScript est au cœur des langages utilisés par les développeurs web.  

## Qu’est-ce qu’une variable ?  
Une variable est un conteneur servant à stocker des informations de manière temporaire, comme une chaine de caractères (un texte) ou un nombre par exemple. 

Le propre d’une variable est de pouvoir varier, c’est-à-dire de pouvoir stocker différentes valeurs au fil du temps et c’est cette particularité qui les rend si utiles.
## Les règles de déclaration des variables en JavaScript

Pour pouvoir utiliser les variables et illustrer leur intérêt, il va déjà falloir les créer. Lorsqu’on crée une variable en JavaScript, on dit également qu’on « déclare » une variable.  

* Le nom d’une variable doit obligatoirement commencer par une lettre ou un underscore (_) et ne doit pas commencer par un chiffre ;
* Le nom d’une variable ne doit contenir que des lettres, des chiffres et des underscores mais pas de caractères spéciaux ;
* Le nom d’une variable ne doit pas contenir d’espace.
***
```
var maChaine = new String("exemple");
var a = 42;
var b = 4.2;
var c = -42;
var d = "42";
alert("ma variable a est de type: "+typeof a+"\nma variable b est de type: "+typeof b+"\nma variable c est de type: "+typeof c+"\nma variable d est de type: "+typeof d);
```

Ce qui donne: ![1er exemple](img/exemple_1.png)  

Les chiffres ont le type number et ce qui est dans les " sont identifié comme une chaine de caractère.
***
```
var machaine = "exemple";
var maChaine = new String("exemple");

alert("ma variable machaine est de type : "+typeof(machaine)+ "\nma variable maChaine est de type : "+typeof(maChaine));
```

Ce qui donne: ![2eme exemple](img/exemple_2.png)  

Le premier on lui donne une nouvelle valeur qui est un string, le 2eme on crée un nouveau donc c'est un objet
***
```
var n = null;
var u = undefined;
var nn = NaN;

alert("ma variable n est de type : "+typeof(n)+ "\nma variable u est de type : "+typeof(u)+"\nma variable nn est de type : "+typeof(nn));
```

Ce qui donne: ![3eme exemple](img/exemple_3.png)  


***
