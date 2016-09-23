# Titles

As we started writing a markdown document, we need to add a title and some sub-headers.

Markdown supports two styles of headers, Setext and atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:

```
This is an H1
=============

This is an H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---
Traduction:
#Les titres

Pour commencer à écrire un document Markdown, nous avons besoin de titre et de sous-titre.

Markdown accepte deux styles d'en-tête, le Setext et l'atx.

Le style Setext est souligné à l'aide du signe "égal" (pour le permier niveau d'en-tête) et du signe "tiret" (pour le second niveau d'en-tête). Par exemple:

```
C'est un H1
===========

C'est un H2
-----------
```
Le nombre de signes = ou - n'aura pas d'importance.

L'en-tête de style Atx le hashtag de 1 à 6 en début de ligne, cela correspond aux en-têtes de niveaux 1 à 6. Par example:

```
#C'est un H1

##C'est un H2

######C'est un H6
```
Vous pouvez, en option, fermer les en-têtes de style atx. c'est purement esthétique - vous pouvez l'utiliser si vous pensez que le rendu visuel est mieux. Le hashtag de fermeture n'a pas besoin d'être associé au nombre de hashtag d'ouverture. (Le nombre de hashtag d'ouverture détermine le niveau de l'en-tête.):

```
#C'est un H1#

##C'est un H2##

###C'est un H3####### 
```



