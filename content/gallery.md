---
Title: Gallery
Description: Mitt galleri
Template: gallery # looking for gallery.twig
---

<!--

Vi behöver inte göra något riktigt så avancerat som Instagram, men vi vill ha ett galleri på sidan som kan visa upp bilder som en blogg eller bilder på olika projekt ni arbetat med.

#Förkunskaper
Du har jobbat igenom artikeln “Cimage - Hur fungerar det?” som går igenom verktyget Cimage.

Du har jobbat igenom artikeln “Hur kan vi göra bilder och video responsivt?” som går igenom hur vi kan ladda in bilder på ett responsivt sätt.

Du har jobbat igenom uppgiften “Bygg om din rapport-sida med CSS-Grid” där du har skapat ett grid för din rapport-sida.

#Krav
Uppgiften är två delad, grid-delen och bildhanterings-delen.


Gridet
Välj antalet kolumner du vill ha i ditt grid.
I desktop ska det vara minst tre kolumner.
På mobil ska det vara en kolumn.
Varje “box” i gridet ska ladda in en bild.
Trycker man på bilden ska man hamna på en sida som visar enbart bilden.
Exempel: Bilden längst upp på denna sidan.
Sidan skall vara responsiv på samma sätt som er rapport-sida.
Bilderna
Det ska inte finnas dubbletter i gridet.
Bildernas storlek ska optimeras med hjälp utav Cimage.
Tips: Minska storleken, ändra filformat eller sänk kvalitén.
Bilderna ska laddas i minst två olika storlekar med hjälp utav srcset.
En storlek när gridet har en kolumn i bredd.
En storlek när gridet har tre kolumner i bredd.
Tips: Cimage kan hjälpa dig med storleken på bilden.
När man trycker på bilden (så den öppnas i ny flik) så ska den öppnas i sin ursprungliga storlek.
Samtliga bilder som används ska du ha rätt att använda.
Använd egna bilder eller någon av de tjänster som finns tillgängliga här.
#Övrigt
Dina .scss filer ska gå igenom lint med hjälp utav npm run lint.

Dubbelkolla att allt fungerar på studentservern.

När du laddat upp till studentservern kan du testköra sidan på mobilen och se så att allt fungerar.

///// BILDER /////

///// ADJUST WIDTH /////

![Leaf](../image/leaf_256x256.png?w=150&h=150)
?w=150&h=50&stretch)
?w=150&h=50&crop-to-fit)
?w=150&h=50&fill-to-fit=660000)
?w=150&h=50&&no-upscale)


///// METHODS TO AFFECT FILE SIZE /////
// CHOOSE FILE FORMAT
?width=50%&save-as=jpg/png/gif)

 // REDUCE WIDTH AND FILE SIZE
?width=50%)

// ONLY REDUCE FILE SIZE (start by q=10 and increase 10 each step)
?width=50%&q=50)

// CROP
&area=30,0,0,0&save-as=png) // crop images top,right,bottom,left


///// FILTER /////
&convolve=lighten
&convolve=darken
&blur
&f=grayscale
&f=brightness,50
&f=contrast,50

///// CACHE /////
?nc // no-cache, återskapar bilden ifall cache går fel
?v // nästa steg, lägga på verbose output. Öppnar bilden i ny flik för att se utskriften om det tar en stund att ladda in


-->
<!-- Cimage fungerar endast vid förfrågan av dbwebbs Apache-server till image för att nå mappen assets/img -->
<div class="wrapper grid">
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/01.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset='image/gallery/01.jpg?width=50%&q=40'>
        <source media="(min-width: 376px)" srcset='image/gallery/01.jpg?width=50%&q=70'>
        <a href="image/gallery/01.jpg" target="_blank"><img src='image/gallery/01.jpg?width=50%&q=40' class="max-width" alt="wolf"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/02.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/02.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/02.jpg?width=50%&q=70">
        <a href="image/gallery/02.jpg" target="_blank"><img src="image/gallery/02.jpg?width=50%&q=40" class="max-width" alt="lion cub"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/03.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/03.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/03.jpg?width=50%&q=70">
        <a href="image/gallery/03.jpg" target="_blank"><img src="image/gallery/03.jpg?width=50%&q=40" class="max-width" alt="elephant"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/04.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/04.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/04.jpg?width=50%&q=70">
        <a href="image/gallery/04.jpg" target="_blank"><img src="image/gallery/04.jpg?width=50%&q=40" class="max-width" alt="moose"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/05.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/05.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/05.jpg?width=50%&q=70">
        <a href="image/gallery/05.jpg" target="_blank"><img src="image/gallery/05.jpg?width=50%&q=40" class="max-width" alt="killer whale"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px?)" srcset="image/gallery/06.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/06.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/06.jpg?width=50%&q=70">
        <a href="image/gallery/06.jpg" target="_blank"><img src="image/gallery/06.jpg?width=50%&q=40" class="max-width" alt="bear"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/07.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/07.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/07.jpg?width=50%&q=70">
        <a href="image/gallery/07.jpg" target="_blank"><img src="image/gallery/07.jpg?width=50%&q=40" class="max-width" alt="monkey"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/08.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/08.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/08.jpg?width=50%&q=70">
        <a href="image/gallery/08.jpg" target="_blank"><img src="image/gallery/08.jpg?width=50%&q=40" class="max-width" alt="eagle"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/09.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/09.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/09.jpg?width=50%&q=70">
        <a href="image/gallery/09.jpg" target="_blank"><img src="image/gallery/09.jpg?width=50%&q=40" class="max-width" alt="penguin"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/10.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/10.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/10.jpg?width=50%&q=70">
        <a href="image/gallery/10.jpg" target="_blank"><img src="image/gallery/10.jpg?width=50%&q=40" class="max-width" alt="cat"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/11.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/11.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/11.jpg?width=50%&q=70">
        <a href="image/gallery/11.jpg" target="_blank"><img src="image/gallery/11.jpg?width=50%&q=40" class="max-width" alt="zebra"></a>
    </picture>
    <picture>
        <source media="(min-width: 1280px)" srcset="image/gallery/12.jpg?width=50%&q=40">
        <source media="(min-width: 800px)" srcset="image/gallery/12.jpg?width=50%&q=40">
        <source media="(min-width: 376px)" srcset="image/gallery/12.jpg?width=50%&q=70">
        <a href="image/gallery/12.jpg" target="_blank"><img src="image/gallery/12.jpg?width=50%&q=40" class="max-width" alt="squirrel"></a>
    </picture>
</div>
