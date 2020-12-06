---
Title: Load
Description: Min sida för load.
Template: analysis # looking for analysis.twig
---

# Load

I denna uppgift ska jag analysera tre olika webbplatser utifrån deras:

- snabbhet att laddas
- aspekter utifrån laddningstid och användbarhet som kan förbättras

## Urval

Jag ville göra ett brett urval av olika typer av kända sidor. Mitt urval blev därför en nyhetssida, en bildfokuserad sida och en företagssida med en reklamvideo:

- [Expressen](https://www.expressen.se/) (nyhetssida)
- [Flickrs Explore-sida](https://www.flickr.com/explore) (foton)
- [Prodma.se]() (företag)

## Metod

Följande tillvägagångssätt kommer att tillämpas vid analysen av de tre sidorna:

1. Testa hur snabbt sidan laddas genom verktyget [PageSpeed](https://developers.google.com/speed/pagespeed/insights/?hl=sv).

- Rött (0-49) = dåligt
- Orange (50-89) = behöver förbättras
- Grönt (90-100) = bra

2. Värdena från PageSpeed dokumenteras i detta [Google SpreadSheet](https://docs.google.com/spreadsheets/d/1WJwWwucQqcMfdFIssg1CxnlBZwSN4Q1deDBuywobMyc/edit?usp=sharing)

<!--
Ta en snapshot (bild) på webbplats.
Dokumentera och visualisera färgpaletten som används.
Notera vilken typ av färgschema som använts.
Notera om och vilken accentfärg som använts.
Notera val av typsnitt för H1-H3 samt brödtext, kommentera om det är serif eller sans-serif.
Notera i en mening om du anser att webbplatsens färgval och typografi motsvarar den profil du tror att webbplatsen vill ha.

Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg.
-->

## Resultat

<table>
    <thead>
        <tr>
            <th><h3>Expressen</h3></th>
            <th><h3>Flickr Explore</h3></th>
            <th><h3>Prodma.se</h3></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="../assets/img/5_expressen.png"><img src="../image/5_expressen.png?q=10" alt="Expressen"></a>
            <a href="https://www.expressen.se/">https://www.expressen.se/</a>
            </td>
            <td><a href="../assets/img/5_flickr.png"><img src="../image/5_flickr.png?q=10" alt="Flickr Explore"></a>
            <a href="https://www.flickr.com/explore">https://www.flickr.com/explore</a>
            </td>
            <td><a href="../assets/img/5_prodma.png"><img src="../image/5_prodma.png?q=10" alt="Prodma.se"></a>
            <a href="https://www.prodma.se/">https://www.prodma.se/</a>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Sidornas resultat</h4></td>
        </tr>
        <tr>
            <td colspan="3">
            <a href="https://docs.google.com/spreadsheets/d/1WJwWwucQqcMfdFIssg1CxnlBZwSN4Q1deDBuywobMyc/edit?usp=sharing">Resultat</a>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Förbättringspotential</h4></td>
        </tr>
        <tr>
            <td>
                Sidan minifierar HTML/CSS/JS och använder bilder i rätt storlek, däremot kan främst svarstiden till servern mha CDN förkortas, bilder som inte syns på skärmen väntas med att läsas in och JS-kod som inte används rensas bort. Detta kan påverka PageSpeed-värdet positivt och göra att sidan laddas snabbare, vilket ökar användarens upplevelse, samt hamnar högre upp vid sökresultat i Google (Google 2020, MOZ 2020)
            </td>
            <td>
                Sidan minifierar HTML/CSS/JS och använder bilder i rätt storlek, däremot kan bilder som inte syns på skärmen väntas med att läsas in, ett modernare bildformat (som JPEG 2000 och WebP) användas och JS-kod som inte används rensas bort. Detta kan påverka PageSpeed-värdet positivt och göra att sidan laddas snabbare, vilket ökar användarens upplevelse, samt hamnar högre upp vid sökresultat i Google (Google 2020)
            </td>
            <td>
                Sidan minifierar HTML/CSS/JS och skjuter upp inläsning av bilder som inte syns på skärmen, däremot kan svarstiden till servern förbättras mha CDN, bilder med rätt storlek användas samt JS- och CSS-kod som inte är lika viktiga läsas in i slutet av sidan. Detta kan påverka PageSpeed-värdet positivt och göra att sidan laddas snabbare, vilket ökar användarens upplevelse, samt hamnar högre upp vid sökresultat i Google (Google 2020)
            </td>
        </tr>
    </tbody>
</table>

## Analys

När alla sidorna laddas om genom ctrl+shift+r laddas allt fler resurser och därmed ökar också sidans storlek. På så sätt kan vi scrolla igenom sidan snabbare utan att behöva ladda in nytt innehåll. Problemet ovanstående sidor verkar ha är främst följande:

- **Responstiden till servern tar för lång tid**. Detta kan förbättras genom att använda en CDN (content distribution networks) som lagrar filerna i olika datacentrum världen över för snabbare åtkomst.
- **Onödig JS-kod**. Kan förbättras genom att rensa bort det som inte behövs.
- **Bilder läses in för tidigt**. Genom att läsa in bilder först när de syns på skärmen kan sidan starta upp snabbare.
- **Inte anpassad bildstorlek**. Genom att anpassa bilder till olika enheter mha picture-elementet kan sidan ladda upp snabbare.
- **Modernare bildformat**. Fundera över ifall användningen av exempelvis JPEG 2000 och WebP kan förbättra sidan PageSpeed-värde.

Ingen av sidorna gjorde ett särskilt bra resultat i testet men den som gjorde bäst ifrån sig var [Expressen](https://www.expressen.se/), vars PageSpeed-värde uppgick till 52 i mobilt läge och 83 i desktop-värde. Det finns dock möjligheter till förbättringspotential enligt ovan nämnda åtgärder.

För egen del så skulle jag nog säga att en sekunds laddningstid är riktigt snabbt, 2-3 sekunder vad jag förväntar mig och därutöver långsammare. Hur länge man orkar vänta beror också till stor del på hur intressant sidan verkar vara. Jag upplevde att Expressen laddade upp snabbt, Flickr hade en normal laddtid medan Prodma var relativt långsam vilket också stämmer relativt väl överens med PageSpeed-värdena.

## Referenser

- Google (2020). _PageSpeed Insights_. https://developers.google.com/speed/pagespeed/insights/?hl=sv (2020-11-29).
- MOZ (2020). _Page Speed_. https://moz.com/learn/seo/page-speed (2020-11-29).

## Övrigt

Jag som skrivit denna rapporten heter Johan Kristoffersson och går på programmet Webbprogrammering på distans 120hp. Kursen heter design och går under HT20.
