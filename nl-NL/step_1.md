<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**CSS-animaties**</span> worden gebruikt om de aandacht van mensen te trekken en een website aantrekkelijk te maken zonder het laden van pagina's te vertragen. De animaties werken door een of meer eigenschappen van een element in de loop van de tijd te veranderen. Voorbeelden van animaties zijn hover-effecten, het laden van afbeeldingen, tekstanimatie, deeltjeseffecten en geanimeerde afbeeldingen. 
</p>

Je kunt HTML en CSS gebruiken om animaties te maken die elementen op een webpagina wijzigen.

Een CSS `@keyframes` regel kan worden ingesteld om na verloop van tijd te veranderen. Je kunt kleur, positie, grootte, rotatie en vele andere eigenschappen veranderen.

`@keyframes` bepalen hoe het element eruit moet zien wanneer een percentage van de lopende animatie is voltooid.

Het startproject bevat een `animation.css` bestand met op maat gemaakte animaties die kunnen worden gebruikt om je inhoud tot leven te brengen.

De startanimaties zijn:

- `spinme`
- `bounceme`
- `scaleme`
- `rollmeleft`
- `rollmeright`
- `movemeleft`
- `movemeright`

Voeg de animatie als een class toe aan het object dat je wilt animeren.

## --- code ---

language: html
filename: index.html
line_numbers: false
--------------------------------------------------------

<section class="xcenter">
  <h2 class="scaleme">Animaties</h2>
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
