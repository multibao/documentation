---
author: ""
description: null
published: false
title: Untitled
---



# Charte de nommage, ou le B.a.-ba de ce que je dois savoir pour nommer un fichier

> La charte de nommage doit être respectée lorsque vous nommez une image, une fiche, un dossier, un dépôt de fiches, une organisation ... Cette section concerne tout contributeur.

## Utiliser des caractères normaux uniquement

**On peut utiliser**
* les 26 lettres françaises non accentuées, majuscules et minuscules ;
* les 10 chiffres ;
* ‘_’ (dit ‘souligné’ ou ‘underscore’ en anglais, ou encore ‘tiret du 8’ en langage dactylo) : à utiliser systématiquement pour remplacer un espace ;
* ‘-’ (dit ‘tiret’ ou ‘tiret du 6’) : à utiliser pour remplacer la préposition ‘de’.

**On ne peut pas utiliser**
* les accents: é è ô î â etc...
* les caractères spéciaux: @ # | & etc...

**Exemple:** ne pas nommer une fiche "forum-ouvert&world-café.md" mais "forum_ouvert_world-cafe" 

## Utiliser uniquement des miniscules 

MultiBàO ne reconnaît pas les noms de fichiers avec des majuscules. 

**Exemple 1:** ne pas nommer une fiche "Forum_Ouvert_Ecole_Benjamin.md" - multiBàO ne pourra pas faire apparaître la ressource. Mais plutôt nommer la fiche: "forum_ouvert_ecole_benjamin.md".

**Exemple 2:** ne pas nommer une dossier "Nos_Forums/forum_ouvert_ecole_benjamin.md" mais "nos_forums/forum_ouvert_ecole_benjamin.md".

## Ecrire court

* les articles et prépositions comme "mais; et; avec; sur; dans; etc." sont à éviter

**Exemple:** plutôt que de nommer une fiche "Forum-Ouvert-avec-la-méthode-ecole-Benjamin-du-34.md", la nommer "forum_ouvert_ecole_benjamin.md"

## Ne pas changer le nom des fichier en cours de route

Imaginons qu'un site extérieur, comme http://coop-tic.eu écrive un article sur les bonnes pratiques d'animation en réunion et qu'il y soit indiqué un lien vers la fiche multiBàO que vous avez écrit. 

Si vous avez changé le nom de votre ressource, ce lien sera obsolète et les lecteurs tomberont sur une page d'erreur. 

Il en est de même pour l'utilisation du script d'intégration: ce dernier permet à n'importe quel utilisateur de multiBàO d'intégrer votre fiche / une fiche à son site web, en prenant automatiquement la mise en page de son site. Si vous modifiez le nom de la ressource, celle-ci n'apparaîtra plus sur son site web, ni sur tous les autres sites qui partagent votre ressource. 

## Nommer le language utilisé

Maintenant que vous avez en main les bonnes pratiques pour nommer un fichier, une organisation, un dépôt, vous pouvez vous intéresser à la petite partie juste après le nom, ".md" dans les exemples cité ci dessus.

Ce ".md" signifie que le fichier a été écrit en langage Markdown. Vous pourrez trouver d'autres formats comme par exemple:
* .html, pour langage HTML
* .js pour langage Java Script
* .png pour les images au format PNG

**Exemple:** si vous nommez une fiche "forum_ouvert_ecole_benjamin", elle n'apparaîtra pas sur multiBàO. Nommez la "forum_ouvert_ecole_benjamin.**md**" et elle apparaitra puisque vous avez écrit une fiche en language Markdown (le language utilisé dans l'éditeur et sur github), et que vous avez indiqué à multiBàO que c'est écrit dans ce language.
