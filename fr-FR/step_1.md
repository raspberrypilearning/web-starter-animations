<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Les animations CSS**</span> sont utilisées pour attirer l'attention des gens et rendre un site web attrayant sans ralentir le temps de chargement d'une page web. Les animations fonctionnent en modifiant une ou plusieurs propriétés d'un élément au cours d'une période donnée. Les exemples d'animations sont les effets de survol, le chargement d'images, l'animation de texte, les effets de particules et les images animées. 
</p>

Tu peux utiliser HTML et CSS pour créer des animations qui modifient les éléments d'une page web.

Une règle CSS `@keyframes` peut être modifiée au fil du temps. Tu peux modifier la couleur, la position, la taille, la rotation et bien d'autres propriétés.

`@keyframes` contrôle l'apparence de l'élément lorsqu'un pourcentage de l'animation en cours est terminé.

Le projet de démarrage contient un fichier `animation.css` avec des animations personnalisées qui peuvent être utilisées pour donner vie à ton contenu.

Les animations de démarrage sont :

- `spinme`
- `bounceme`
- `scaleme`
- `rollmeleft`
- `rollmeright`
- `movemeleft`
- `movemeright`

Ajoute l'animation en tant que classe à l'objet que tu veux animer.

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="xcenter">
  <h2 class="scaleme">Animations</h2>
</section>
      
<section class="xcenter">
 <p class="bigfont rollmeleft">🐶</p>
 <p class="bigfont bounceme">🐶</p>
 <p class="bigfont rollmeright">🐶</p>
</section>  
      
<section class="xcenter">
  <p class="bigfont movemeleft">🐶</p>
  <p class="bigfont spinme">🐶</p>
  <p class="bigfont movemeright">🐶</p>
</section>

--- /code ---

<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/animation-examples" width="600" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
