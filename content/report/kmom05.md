---
Title: Kmom05
Description: Min sida för kmom05
Template: kmom
---

# Kmom05

<div class="embed-container">
    <iframe src="https://www.youtube.com/embed/9zBsdzdE4sM" frameborder="0" allowfullscreen></iframe>
</div>

Efter att ha studerat PageSpeed för sidorna har jag noterat att de verkar mer optimerade för desktop-versionen än för mobila enheter. De mobila enheterna visade i alla tre fallen på betydligt sämre värden. Det som till stor del verkar bestämma detta är en bristfällig bildoptimering för mobila enheter. Jag märkte även att laddningstiden enligt devtools ökade exponentiellt för varje refresh med ctrl+shift+r då fler requests gjordes. Däremot märkte jag inte av det personligen. Det kan bero på att filer cache-lagras för att snabba upp sidan för användaren inför nästa besök.

Cimage är ett snabbt verktyg för att komprimera (och till viss del använda filter på) bilder. Den stora nyttan med det är att bilder laddas snabbare då man kan göra justeringar i filstorleken utan att bildkvaliteten försämras märkvärt. Jämfört med verktyg som Photoshop så går det mycket snabbare att använda och du slipper skapa flera filer för ditt ändamål. Nackdelen med att ha många filer är att du lätt tappar överblickbarheten. Dessutom blir det problematiskt om du skulle behöva göra ytterligare någon justering. Med en enda originalfil som du kan bearbeta i browsern med några tecken kod i Cimage blir arbetet med bilder mycket mer lätthanterligt.

Genom att aktivt jobba med bildstorleken och responsivitet så bidrar det till flera fördelar.

- användaren upplever sidan som snabbare och mer användarvänlig
- chansen att användaren klickar sig vidare på olika sidor bör öka om den känns snabb.
- sidan ger ett proffsigare intryck
- det går att beskära bilder och därmed ändra fokus i bilden beroende på responsivitet vilket kan skapa större intresse.
- det tillåter användare med äldre browsers som ännu inte stöder picture-elementet (dock utan responsiviteten)
- sidan får högre resultat i PageSpeed vilket kan göra att den hamnar högre upp i Googles sökmotor.

Min TIL för kursmomentet är att ett aktivt arbete med bildhantering är en viktig process i arbetet att hålla kvar besökarens intresse och få fler besökare. Detta arbete behöver inte vara någon komplicerad process med multipla bilder skapade i Photoshop.
