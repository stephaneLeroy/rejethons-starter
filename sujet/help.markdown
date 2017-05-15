---
layout: page
---

# Markdown

Le markdown est une syntaxe simple permettant de formater du text.

Vous trouver une documentation fournie [ici](https://guides.github.com/features/mastering-markdown/)


# Jekyll et outils de ce site

Pour simplifier certaines taches, vous avez a disposition certain outils

#### Vous pouvez facilement inclure une video youtube
```
{{ "{% include youtube.html vid='votre VID' " }}%}
```
Exemple :
{% include youtube.html vid="E_A4wsvXxLY" %}


#### Vous pouvez mixer markdown et HTML
Pour information, bootstrap et font awesome sont disponibles de base
```
<div class="badge">
  <span class="fa fa-bullhorn fa-2x"></span>.....Tadaaam!
</div>
```
Resultat :

<div class="badge">
  <span class="fa fa-bullhorn fa-2x"></span>.....Tadaaam!
</div>

On aurait donc pu inclure la video precedente ainsi :
```
<iframe class="center-block" width="560" height="315" src="https://www.youtube.com/embed/E_A4wsvXxLY?ecver=1" frameborder="0" allowfullscreen></iframe>
```
