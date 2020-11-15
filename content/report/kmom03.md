---
Title: Kmom03
Description: Min sida för kmom03
Template: kmom
---

# Kmom03

Det har gått relativt bra att arbeta med Grid och flexbox. För detta kursmoment har jag endast använt mig av grid då jag kunde göra allt jag behövde för kursmomentet genom det.

Även om jag inte använde mig av flex är området inte obekant för mig. I en tidigare kurs med HTML/CSS har jag gjort en hemsida där grid och flex var mycket i fokus. Ni hittar den här: [Djupviks hamn](http://s0c4j45.dwapp.se/). Beroende på vilken man använder så har de olika fördelar:

Grid är mer användbart när man vill strukturera ut elementen på en sida. Det är lättare att skapa en grundläggande skiss för en sida med hjälp av grid. Min favorit-property i grid är grid-template-areas där du kan skapa ett rutnät och sedan placera ut de olika elementen var du vill. Det känns naturligt att strukturera ut elementen på detta sätt.

Flex är lämpligt när man vill lägga något horisontellt och på lika avstånd från varandra. Detta passar bra vid horisontella menyer. Det är även lätt att växla mellan horisontell och vertikal layout vid olika media queries med flex-direction. Dessutom gillar jag align-items: flex som gör att jag kan stretcha flexbarnen (t ex divs) och få dem att hamna på samma höjd, bra när man vill få bild och text att hamna på samma höjd. Jag använder dem när jag vill ha element på samma rad och brukar lägga

När jag skapade SCSS-koden så gjorde jag dels en modul kallad kmom.scss som stylar om varje kmom-sida. Dessutom gjorde jag en report.scss som landningssida för alla kmoms. På så sätt blir det lite mera struktur och jag vet vad varje modul ändrar.

Jag hade som mål förra gången att göra om sidan så att jag fick en hero-image. För detta var jag tvungen att göra ändringar i index.twig där jag fick lägga titel och navigering inuti klassen "hero-image". Utöver det så använde jag mig av CSS-propertyn "filter:" och ändrade grayscale samt brightness för att loggan skulle smälta in bättre med himlen. Är överlag nöjd med hur det blev, bättre än kmom02.

Mitt TIL för denna gång är att grid och flexbox skapar nya möjligheter för att strukturera upp innehållet på sidan. Placeringen av elementen blir mycket lättare och behärskar man teknikerna går det snabbare att strukturera upp sina sidor och skapa en attraktiv layout.
