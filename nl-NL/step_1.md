<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**CSS animations**</span> are used to grab people's attention and make a website engaging without slowing down how long it takes to load a webpage. The animations work by changing one or more properties of an element over a period of time. Examples of animations are hover effects, loading images, text animation, particle effects, and animated images. 
</p>

You can use HTML and CSS to create animations that change elements on a webpage.

A CSS `@keyframes` rule can be set to change over time. You can change colour, position, size, rotation, and many other properties.

`@keyframes` control how the element should look when a percentage of the running animation is complete.

The starter project contains an `animation.css` file with custom-made animations that can be used to bring your content to life.

The starter animations are:

- `spinme`
- `bounceme`
- `scaleme`
- `rollmeleft`
- `rollmeright`
- `movemeleft`
- `movemeright`

Add the animation as a class to the object you want to animate.

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

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

\--- /code ---

<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/animation-examples" width="600" height="500" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
