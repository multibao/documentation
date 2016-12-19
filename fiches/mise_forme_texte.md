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

Insérer du code informatique lisible et réutilisable dans sa fiche :`
{% for post in site.posts %}
{% for cat in post.categories %}
{% if cat == page.category %}



<div class="post postContent">
  <div  class="postDate"><time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">{{ post.date | date: "%b %-d, %Y" }}</time>
  </div>
  <div class="postTag">
    {{post.tag}}
  </div>
  <br>
  <div class="postTitle">
  <a class='postLink' href="{{site.url}}{{site.baseurl}}{{post.url}}">{{post.title}}</a>
  </div>
  <div class="postExt">
    {{post.excerpt}}
  </div>
</div>
{% endif %}
{% endfor %}

{% endfor %}`

s'écrit entre les symboles  ``` {mon code} ```
