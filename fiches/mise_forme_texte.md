# Mettre en forme le texte

# Titre 1

s'écrit \# Titre 1

## Titre 2 

s'écrit  \#\# Titre 2 

De même pour \#\#\# Titre 3, \#\#\#\# Titre 4, etc. 

## Gras et italique

**je suis un peu gras** s'écrit \*\* je suis un peu gras\*\*
*je suis italique* s'écrit \*je suis italique\* (ça se dit, ça?)

## Puces

* à la claire fontaine
* j'ai bu d'leau cristaline®

s'écrit 

\* à la claire fontaine

\* j'ai bu d'leau cristaline®

## Lien hypertexte

[lien vers multiBàO](http://multibao.org) s'écrit \[lien vers multiBàO\]\(http://multibao.org)

## Citation

> « Je veux être un homme heureux, parce que c’est ainsi que l’on fait le bonheur autour de soi. » Sohan Kalim 

s'écrit avec > "texte..." puis passer un ligne pour arréter le mise ne forme de citation

## Code

Insérer du code informatique lisible et réutilisable dans sa fiche :

    {% for post in site.posts %}
    {% for cat in post.categories %}
    {% if cat == page.category %}



    <div class="post postContent">
    <div  class="postDate"><time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">{{ post.date | date: "%b %-d, %Y" }}</time>
    </div>
    <div class="postTag">
    </div>
    
    {% endif %}
    {% endfor %}

    {% endfor %}

Les blocs de code sont soit clôturés par des lignes avec trois «back-ticks» <code>```</code>, soit décalés de quatre espaces depuis le début de la ligne. Une recommande eut être en utilisant les blocs de code clôturé --, ils sont plus faciles à mettre ne place dans la fiche et ils soutiennent la mise en évidence de syntaxe.


## Ligne Horizontale


    3 Tirets 
    ---
   
    3 Asterix
    ***
    
    

Ce qui rend :
---

***
