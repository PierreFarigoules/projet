# Mon premier document en Markdown
## Introduction
### Objectifs

-------
:one: pour ecrire en gras, on utilise les balises ** en ouverture est en fermeture
ainsi
le texte suivant s'écrit de cette forme \*\*Ceci est un texte en gras**
**Ceci est un texte ecris en Gras**

---
:two: Si on souhaite ecrire en italique, on fera la meme manipulation avec juste une * 
*Ici on retrouve un texte en italique*

---
:three: quand on veut barrer du texte on utilisera la touche suivante ~
~~Et la c'est quand on a faux, tout est barré~~

---

:four: Quand on veut lister c'est comme une liste, on mets des tirets.

- Premier élément
- Second
    - Premier sous elem
    -second
- Troisième


Ou bien on peut aussi énumerer dans ce cas là on mets des chiffres suivi d'un point.

1. Etape 1
2. Etape 2
3. Etape 3

---
:five: si on souhaite integrer un lien on doit faire de cette maniere :

\[Visitez google](https://google.com)

[Visitez google](https://google.com)

---
:six: pour ajouter un logo, 

\[descriptif du logo](lien du logo)

![Logo Markdown](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)


# Insertion de code 

pour inserer du code dans un texte on utilisera ces touches \` avant et apres tel que quand on fait \`printf("Hello World !");`
on obtient le resultat suivant 

Voici une ligne de code : `printf("Hello World !");`


Si on doit ajouter un block de code, on utilisera la balise \```` 

si on prends en exemple on peut faire cela 

\````
int a=3;
int b=4;
int c = a+b;
printf("%d",c);
\````

on obtiendra alors ceci :

````
int a=3;
int b=4;
int c = a+b;
printf("%d",c);
````

> "Markdown est simple et efficace !" – Un développeur
> 

Pour les tableaux on va juste utiliser pipe | avec les noms des colonnes. Un exemple sera mieux

\|nom  | prenom|
\|-----|-------|
|ANAS | pedj  |
|ziz|dndnd
jdjd|djdjdj
|djdjd|kdd


|nom  | prenom|
|-----|-------|
|ANAS | pedj  |
|ziz|dndnd
jdjd|djdjdj
|djdjd|kdd


pour faire des cases cochées on va juste faire \- [X] et pour des cases vides \- [ ]


- [X] arrivé a faire des case cochées
- [ ] case non cochées :smile: 

Pour finir, pour les emoji, on fera \:smile\: qui fera apparaitre :smile:

---
<u>Pour souligner, il faut une balise html</u>


