---
Title: Colors
Description: Min sida för colors.
Template: analysis # looking for analysis.twig
---

# Colors

I denna uppgift ska jag analysera tre olika webbplatser utifrån deras:

- färgschema
- val av teckensnitt (serif eller sans-serif)
- inriktning, huruvida färgschemat och typografin uppfyller den bild som sidan försöker framhäva

## Urval

När jag gjorde urvalet ville jag undersöka tre webbplatser med olika inriktningar. Detta för att jag vill träna mig mer i analysen av sidor med olika utgångspunkter och som riktar in sig på olika typer av läsare och kunna se skillnader i hur de väljer att sälja in sitt varumärke och vad de tillhandahåller.

- En webbutik: hur använder de färger och typografi för att sälja olika produkter till kunden?
- En industrisida: hur framhäver de sin industri genom valet av färger och typografi?
- En sida som berör miljön: vilka färger och typografi används för att få fram sitt budskap?

Sidorna jag har valt är:

- [Coolstuff](https://www.coolstuff.se/) (webbutik)
- [Volkswagen](https://www.volkswagen.se/sv.html) (industri)
- [KRAV](https://www.krav.se/) (miljö)

## Metod

Följande tillvägagångssätt kommer att tillämpas vid analysen av de tre sidorna:

1. Print Screen av huvudsidan
2. Plocka ut bildens färgpalett med hjälp av Chrome-extensionen [Site Palette](https://chrome.google.com/webstore/detail/site-palette/pekhihjiehdafocefoimckjpbkegknoh)
3. Notera vilken typ av färgschema som används med hjälp av [Adobe Color](https://color.adobe.com/sv/create/color-wheel)
4. Notera om någon accentfärg används
5. Analysera typsnitet för rubrikerna H1-H3 och brödtexten (och ifall serif eller sans-serif)
6. Notera typsnittet för brödtexten (och ifall serif eller sans-serif)
7. Kommentera i en mening huruvida färgval och typsnitt uppfyller sidans tänkta budskap

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
            <th><h3>Coolstuff</h3></th>
            <th><h3>Volkswagen</h3></th>
            <th><h3>KRAV</h3></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="../assets/img/4_coolstuff.png"><img src="../image/4_coolstuff.png?q=10" alt="Coolstuff"></a>
            <a href="https://www.coolstuff.se/">https://www.coolstuff.se/</a>
            </td>
            <td><a href="../assets/img/4_volkswagen.png"><img src="../image/4_volkswagen.png?q=10" alt="Volkswagen"></a>
            <a href="https://www.volkswagen.se">https://www.volkswagen.se</a>
            </td>
            <td><a href="../assets/img/4_krav.png"><img src="../image/4_krav.png?q=10" alt="KRAV"></a>
            <a href="https://www.krav.se/">https://www.krav.se/</a>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Färgpalett</h4></td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td style="background-color: #f7f7f7">
                        <td style="background-color: #fe931f">
                        <td style="background-color: #bd2726">
                        <td style="background-color: #46b938">
                        <td style="background-color: #428bca">
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td style="background-color: #ffffff">
                        <td style="background-color: #020202">
                        <td style="background-color: #01356a">
                        <td style="background-color: #4dc8f2">
                        <td style="background-color: #6c6b6c">
                    </tr>
                </table>
            </td>
            <td>
                <table>
                    <tr>
                        <td style="background-color: #faf6ed">
                        <td style="background-color: #006844">
                        <td style="background-color: #8ab391">
                        <td style="background-color: #d9735c">
                        <td style="background-color: #69605d">
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Typ av färgschema</h4></td>
        </tr>
        <tr>
            <td>
                <strong>Tetradiskt</strong>
                <p>Två komplementfärgspar (orange med motsatta accentfärgen blått och rött med accentfärgen grönt)</p>
            </td>
            <td>
                <strong>Analogt</strong>
                <p>Närliggande färger</p>
            </td>
            <td>
                <strong>Analogt</strong>
                <p>Närliggande färger</p>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Rubriker</h4></td>
        </tr>
        <tr>
            <td>
                <ul>
                    <li>h1: Shag-Lounge (sans-serif)</li>
                    <li>h2: Shag-Lounge (sans-serif)</li>
                    <li>h3: Shag-Lounge (sans-serif)</li>
                    <li>Brödtext: Source Sans Pro (sans-serif)</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>h1: Helvetica, Arial (sans-serif)</li>
                    <li>h2: Helvetica, Arial (sans-serif)</li>
                    <li>h3: hittades ej</li>
                    <li>Brödtext: vw-text, Helvetica, Arial (sans-serif)</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>h1: caslon-book (sans-serif)</li>
                    <li>h2: Futura (sans-serif)</li>
                    <li>h3: Futura (sans-serif)</li>
                    <li>Brödtext: Futura (sans-serif)</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td colspan="3"><h4>Färg och typsnitt kontra budskap</h4></td>
        </tr>
        <tr>
            <td>
                Sidan innehåller roliga prylar för alla åldrar där basfärgen orange symboliserar glädjen och energin, rött och dess accentfärg grönt representerar julens värme och granens färg och där typsnittet Futura ger ett lekfullt intryck med rundade och asymmetriska former (Beaird 2014).
            </td>
            <td>
                Volkswagens blåa färgschema ger en känsla av stabilitet, ett företag vars bilar du kan lita på håller, och rubrikernas kantiga former utan seriffer ger även det ett stabilt och tungt intryck (Beaird 2014).
            </td>
            <td>
                Ett grön-brunt färgschema som representerar det som växer naturligt på jorden framhäver KRAV:s önskan om att stå för hållbar matproduktion, medan typsnittet som saknar seriffer ger ett seriösare intryck (Beaird 2014, Powell 2002)
            </td>
        </tr>
    </tbody>
</table>

## Analys

Beroende på vilket intryck avsändaren (hemsidan) vill ge så har de valt att använda sig av olika färgteman. När man kommer till CoolStuff ska du känna att här är det roligt, lekfullt och rörelse. Detta märks i både valet av huvudfärg (orange) och i rubrikerna som har "former" och ett informellt och nästan lite småbarnsligt intryck. Eftersom julen är i antågande har sidan ämnat skapa julstämning också, vilket påverkat färgschemat i hög grad. Volkswagen i sin tur försöker ge en känsla av att stabilitet och tyngd. Deras färgval ger en känsla av metallic, allvar och stabilitet. Rubrikerna är kantiga och till viss del fetstilta för att betona denna stabilitet. KRAV:s färgschema försöker fånga känslan för det naturliga och vår jord där den gröna färgen är mörkare för att inte skapa stress. Rubrikerna är versaler och kantiga, vilket skapar ett intryck av att miljön och KRAV-märkning är viktiga saker att beakta. Det man märker överlag med typografin hos alla sidor är att de använder sig av på sin höjd två olika fonter och att de inte blandar olika sans-serifs utan håller sig till en sort, vilket också är vad Beaird (2014) rekommenderar i sitt kapitel om typografi.

## Referenser

- Beaird, J. (2014). The Principles of Beautiful Web Design. 3. uppl., Melbourne: SitePoint.
- Powell, T. (2002). Web Design: The Complete Reference. 2. uppl., New York: McGraw-Hill/Osborne Media

## Övrigt

Jag som skrivit denna rapporten heter Johan Kristoffersson och går på programmet Webbprogrammering på distans 120hp. Kursen heter design och går under HT20.
