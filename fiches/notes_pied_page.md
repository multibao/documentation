
# Insérer des notes de pied de page

### A l'endroit où on souhaite insérer la note

on insère juste le code suivant qui indique que cela est une note avec le numéro correspondant 

Exemple : 

\*\*\[1\]\(\#note\)\*\*  donne **[1](#note)**

\*\*\[2\]\(\#note\)\*\*  donne **[2](#note)**

### A l'endroit où l'on veut que la note pointe

Par exemple à la fin de mon document je crée un chapitre "Sources", section dans laquelle je vais citer les différents auteurs, ouvrages...

J'insère le code html suivant : 

`<a id="note"> <a id="note">`

> On passe en html car le language Markdown n'est pas suffisant pour pouvoir mettre des notes qui renvoient vers les sources. C'est une petite manoeuvre qui sera agréable pour les lecteurs.

Puis les notes en question :

\* \*\*\[1\]\(\#note\)\*\* Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

\* \*\*\[2\]\(\#note\)\*\* Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)

Ce qui donne :

* **[1](#note)** Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

* **[2](#note)** Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)
