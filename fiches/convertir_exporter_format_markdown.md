---
title: Convertir ou exporter un document numérique en format markdown
description: Convertir des fichiers .doc .html ..., ou des documents numériques (hackpad, ...) en format [markdown](http://multibao.org/#multibao/documentation/blob/master/fiches/mise_forme_texte.md) .md.
image_url: 
---

# Convertir ou exporter un document numérique en format markdown

Cette fiche présente comment convertir des fichiers *.doc* *.html* ..., en format [markdown](http://multibao.org/#multibao/documentation/blob/master/fiches/mise_forme_texte.md) *.md*.

## Exporter un hackpad sous la forme d'un fichier markdown

Si le hackpad que vous souhaitez exporter en format markdown est le suivant: https://hackpad.com/OMM-Summer-Camp-24-au-29-juillet-uVe7EIGFThR, alors l'export se fera à partir de l'adresse web suivante: https://hackpad.com/ep/pad/export/uVe7EIGFThR/latest?format=md. L'identifiant du hackpad est *uVe7EIGFThR* est le format demandé *md*. 

Si le hackpad que vous souhaitez exporter en format markdown est le suivant: https://omm.hackpad.com/OMM-Summer-Camp-24-au-29-juillet-uVe7EIGFThR, alors l'esport se fera à partir de l'adresse web suivante: https://omm.hackpad.com/ep/pad/export/uVe7EIGFThR/latest?format=md. Le nom de l'équipe est *omm*.

## Convertir un fichier word sous la forme d'un fichier markdown

1. Enregistrez votre document word sous la forme d'un fichier .docx.
2. [Installez le logiciel pandoc](http://pandoc.org/installing.html)
3. Sélectionnez dans votre terminal où se trouve votre fichier
4. Utilisez la ligne de commande suivante: *pandoc nomdufichier.docx -f docx -t markdown_github -s -o nomdufichier.md*

## Autres conversions vers le format markdown: *odt*, *mediawiki*, *txt*, ...

[Voir la liste des formats supportés par le logiciel Pandoc](http://pandoc.org/index.html)

* Convertion ODT: *pandoc nomdufichier.odt -f odt -t markdown_github -s -o nomdufichier.md*
* Convertion MediaWiki: *pandoc nomdufichier.mediawiki -f mediawiki -t markdown_github -s -o nomdufichier.md*
* Convertion Txt: *pandoc nomdufichier.txt -f txt -t markdown_github -s -o nomdufichier.md*

