<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
A <span style="color: #0faeb0">**CSS animations**</span> are used to grab attention and make a website engaging without slowing down the loading of pages. The animations work by changing one or more properties of an element over a period of time. Examples of animations could be; hover effects, loading images, text animation, particle effects, or animated images. 
</p>

You can use HTML and CSS to create animations that change elements on a web page.

A CSS `@keyframes` rule can be set to change over time. You can change colour, position, size, rotation and many other properties.

`@keyframes` control how the element should look when a percentage of the running animation is complete.

The starter project contains an `animation.css` file with custom made animations that can be used to bring your content to life. 

The starter animations are:
+ Spinme
+ Bounceme
+ Scaleme
+ Rollmeleft
+ Rollmeright
+ Movemeleft
+ Movemeright

<iframe src="https://trinket.io/embed/html/6900625300?toggleCode=true" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Add the animation as a class to the object you want to animate: 

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
