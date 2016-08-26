---
title: Convertir ou exporter un document numérique en format markdown
description: >-
  Convertir des fichiers .doc .html ..., ou des documents numériques (hackpad,
  ...) en format
  [markdown](http://multibao.org/#multibao/documentation/blob/master/fiches/mise_forme_texte.md)
  .md.
image_url: null
published: true
---

# Convertir ou exporter un document numérique en format markdown

Cette fiche présente comment convertir des fichiers *.doc* *.html* ..., en format [markdown](http://multibao.org/#multibao/documentation/blob/master/fiches/mise_forme_texte.md) *.md*.

## Exporter un document hackpad 

En deux minutes et sans effort.

Si l'adresse du hackpad que vous souhaitez exporter en format markdown est la  suivante: 

https://hackpad.com/OMM-Summer-Camp-24-au-29-juillet-uVe7EIGFThR, 

alors l'export se fera à partir de l'adresse web suivante: https://hackpad.com/ep/pad/export/uVe7EIGFThR/latest?format=md. 

L'identifiant du hackpad **uVe7EIGFThR** (en fin d'adresse IP) est le format demandé *md*. 

Dans un nouvel onglet web, placé dans la barre d'adresse : https://hackpad.com/ep/pad/export/**IndentifiantdeMonPad**/latest?format=md. Puis vous cliquez sur Enter pour télécharger le hackapd choisi au format makrdown sur votre ordinateur.

Si le hackpad que vous souhaitez exporter provient d'une organisation il est adressé en format markdown suivant: https://**omm.hackpad.com**/OMM-Summer-Camp-24-au-29-juillet-**uVe7EIGFThR**, 

alors l'esport se fera à partir de l'adresse web suivante: https://**omm.hackpad.com**/ep/pad/export/**uVe7EIGFThR**/latest?format=md. Le nom de l'équipe est *omm*.


Vous pouvez maintenant téléverser votre fichier markdown issu du hackpad sur github en conservant mise en page, texte, photos et liens de redirection comme à l'origine.

## Convertir un fichier word

1. Enregistrez votre document word sous la forme d'un fichier .docx.
2. [Installez le logiciel pandoc](http://pandoc.org/installing.html)
3. Ouvrez une [invite de commande](https://fr.wikipedia.org/wiki/Interpr%C3%A9teur_de_commandes) sur votre ordinateur
4. Sélectionnez dans votre terminal l'empalcement où se trouve le fichier .docx que vous venez d'enregister
5. Utilisez la ligne de commande suivante: *pandoc nomdufichier.docx -f docx -t markdown_github -s -o nomdufichier.md*

## Autres conversions vers le format markdown: *odt*, *mediawiki*, *txt*, ...

[Voir la liste des formats supportés par le logiciel Pandoc](http://pandoc.org/index.html)

* Convertion ODT: *pandoc nomdufichier.odt -f odt -t markdown_github -s -o nomdufichier.md*
* Convertion MediaWiki: *pandoc nomdufichier.mediawiki -f mediawiki -t markdown_github -s -o nomdufichier.md*
* Convertion Txt: *pandoc nomdufichier.txt -f txt -t markdown_github -s -o nomdufichier.md*
