#**Refont web : développement** 🚀 
!!BUG PAS ENCORE RÉSOLUT!!

[Page](https://github.com/Lav000/Refont-design)
![cover](./cover.PNG)
>Cette interface web à l’apparence très propre et bien designée, présente des erreurs de structuration. Les entêtes du document ne sont pas renseignées.
Par simple analyse écrite, minimum une page. Détaillez les points forts et faibles de cette page structurée en  HTML (_div vs semantique_) et css. Dans le validator W3C il y a 9 erreurs à corriger. Du coté css il faut appliquer l'unité de mesure REM :  n'oublié pas de déclarer la racine. Argumentez les erreurs que le développeur commet dans son approche techniques. Il y a également des erreurs d'accessiblité: veuillez m'en décrire quelques uns et m'expliquer la raison. A la fin de votre analyse réalisez la refonte de la page

> *Pour travailler plus confortablement procédez à un clône de ce dépôt git*.
> A la fin de votre réalisation créez un dépôt git avec l'affichage de la page d'index sur le navigateur.
> Trasmettez moi le lien sur mon spread-sheet que je vous est partagé. 
> L'exercice sera  noté /20



><font color="red">**Correction :**</font>\
\
<font color="green">**HTML :** </font>\
**Ligne 10** : balise "div" doit être remplacé par une balise "main" car c'est la partie principale de notre document html\
>**Ligne 12** : balise inutile car nous avons qu'un seul élément à l'interieur\
>**Ligne 13** : balise "h2" soit être remplacé par une balise "img" car il selon sa class il intégrera un logo qui doit être placer dans une balise "img"\
>**Ligne 16** : la balise "div" doit être remplacer par une balise "nav" car c'est un menu de navigation qui est placé à l'interieur\
>**Ligne 26** : balise div a remplacer par une balise "form".\
>**Ligne 27** : le "name" n'est pas renseigné\
>**Ligne 28, 38 et 44** : On ne doit pas utiliser une balise "button" car un button ne peut pas contenir ou ne peut pas être positionné dans une balise "a", on doit donc utiliser seulement une balise "a" en lui attribuant la class "button" par exemple\
>**Ligne 32** : balise "div" peut être remplacé par une balise "section" car le contenue interieur est une section de la page\
>**Ligne 33** : la balise "span" devrait être accompagné d'un id ou d'une classe\
>**ligne 40** : la balise "div" doit être remplacé par la balise "form" car il sagit d'un formulaire\
>**Ligne 43** : La valeur de l'attribut "name" n'a pas de valeur\
>**Ligne 47** : La balise "a" est fermé deux fois\
>**Ligne 50** : La balise "div" peut être remplacé par une balise "nav". On peut également ajouter l'attribut aria-label a la nav ainsi que pour tous ses éléments\
>**Ligne 59 et 60** : Les balises fermante "div" sont inutile car elles n'ont pas été ouverte\
>On peut aussi souligner que cette page ne possède pas de balise "footer"\
\
<font color="green">**CSS :** </font>\
>Toutes les unités doivent être convertie en rem.\
Pour ce faire on doit initialisé le font-size: 62.5%;
Ensuite on utilise cette formule : 16*62.5% = 10.000

![AUR license](https://img.shields.io/aur/license/c)