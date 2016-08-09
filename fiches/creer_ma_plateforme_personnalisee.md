# Créer ma propre plateforme de dépôts

Vous avez la possibilité de créer une plateforme collaborative personnalisée avec les mêmes fonctionnalités de multiBàO.org.

**Insérer ici un exemple réalisé comme le Summercamp**

## Etape 1: installer multibao sur votre compte

1. [Inscrivez vous sur github.com/join et connectez vous avec votre compte utilisateur](http://multibao.org/#multibao/documentation/blob/master/fiches/creer_compte.md)
2. Rendez vous sur [https://github.com/daktary-team/daktary](https://github.com/daktary-team/daktary), qui est l'espace où la technologie http://multibao.org est hebergée
3. Cliquez sur l'icône *Fork*, en haut à droite de votre écran. En cliquant sur *Fork* vous dupliquez le site daktary sur votre propre compte.

Vous avez maintenant une copie de multiBàO sur votre compte.

## Etape 2: générer votre site personnalisé

### Option 1: avec votre nom de domaine.fr,.com,.org,...

1. Éditez le fichier *CNAME* et remplacez le nom de domaine http://multibao.org par votre nom de domaine.
2. Renseignez les informations à votre fournisseur de domaine DNS.

### Option 2: vous n'avez pas de nom de domaine

1. Supprimez le fichier *CNAME*.
2. Votre site est dès maintenant disponible sur https://*votrenomdecompte*.github.io/daktary/. 

## Etape 3: personnalisez votre site

### Pour modifier le titre principal *multiBàO*

1. Ouvrez dans le fichier *index.html*.
2. Modifiez la balise *title* dans le *header*.
3. Modifiez le titre dans le *body* : 
\<\h1>\<\a href="">multi\<\span>BàO\<\/span>\<\/a>\<\/h1>.

### Pour modifier l'image de la page d'accueil

1. Dans le dossier *img*, ouvrez le fichier *home-intro.jpg*. 
2. Supprimez ce fichier. 
3. Remplacez ce fichier par votre image. Cette image doit être au format *jpg*, être nommée: *home-intro.jpg*, et être en format *1280 x 431 px*. Glissez votre fichier d'image *home intro* dans le dossier "img" et sauvegardez. 

### Pour modifier les deux phrases de présentation et la désignation des 2 boutons (page d'accueil)

1. Éditez le fichier *config.js*
2. Remplacez les éléments suivants par les éléments souhaités:

MULTIBAO.UVP1 = '*S\'inspirer des autres cultures*'

MULTIBAO.UVP2 = '*Rédiger et partager vos expériences*'

MULTIBAO.BUTTON1 = '*Commencer ici*'

MULTIBAO.BUTTON2 = '*Guide d\'utilisation*'

### Pour modifier les dépôts ou dossiers ou fichiers à faire apparaître via la page d'accueil

1. Éditez le fichier *config.js*
2. A la place de GH.OWNER = '*multibao*', remplacez *multibao* par votre nom de compte (celui sur lequel vous avez forké votre site).
3. Sur votre compte, créez un repository sur [new repository](https://github.com/repositories/new) que vous nommerez *organisations*
4. Créez votre première fiche, avec le format *nomdelafiche.md*
5. Indiquez les éléments suivants:

\---

title: *deuxième titre*

label: *premier titre*

owner: *lien du dépôt, dossier ou fichier que vous souhaitez faire apparaître*

\---

Vous trouverez [ici](https://github.com/multibao/organisations) des exemples existants.

### Pour modifier le CSS

* Éditez le fichier *custom.css*













