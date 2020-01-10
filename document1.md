# En quoi consiste Markdown?

<div style="text-align: justify">

**Markdown** est un type de syntaxe permettant la modification du style d'un texte sur le web. Grâce à l'utilisation de quelques caractères non-alphabétiques (par exemple: ` # ` ou ` * `), il est possible de faire apparaître le texte ciblé en **gras** ou en *italique*, d'ajouter des images, ou encore de créer des listes parmi tant d'autres choses. 

</div>

Sur **GitHub**, la syntaxe Markdown peut être utilisée à différents endroits:

* Les gists
* Les commentaires dans les *Discussions* et les *Demandes d'extraction* (Pull Requests)
* Les fichiers ayant ```.md``` ou ```.markdown``` comme extension.

# Guide de la syntaxe

Voici une vue d'ensemble de ce que la syntaxe Markdown permet de faire sur [GitHub](http://github.com) ou dans ses propres fichiers texte.

## Titres

### Ceci est un titre
##### Ceci est également un titre
###### Ceci est toujours un titre

Le symbole `#` permet de configurer la ligne de texte qui suit comme étant un **titre**. Il peut être utilisé *plusieurs fois* afin de créer un sous-titre à chaque fois moins important.

```
# Ceci est un titre
#### Ceci est également un titre
###### Ceci est toujours un titre
```

## Accentuation

*Ce texte est en italique*

**Ce texte est en gras**

_Il est **possible** de les combiner_

Pour accentuer un texte (en *italique* ou en *gras*, par exemple), il suffit d'entourer la portion de texte souhaitée par les symboles `*`ou `_`(italique), ou `**`ou `__`(gras).

```
*Ce texte sera en italique*
_ Ce texte sera également en italique_

**Ce texte sera en gras**
__Ce texte sera également en gras__

_Il est **possible** de les combiner_
```

**Attention:** bien qu'il existe deux manières différentes d'accentuer son texte, celles-ci ne sont pas interchangeables (**cette portion de texte ne sera pas en gras__).