---
Title: Kmom10
Description: Min sida för kmom10
Template: kmom
---

# Kmom10

## Uppdrag 1 - webbplats

Jag bestämde mig för att göra en sida om advokater och började med att leta upp några olika exempel på advokatsidor för att få lite inspiration och sparade bilder på dessa. Med hjälp av dessa formulerade jag en egen text för min about-sida som berättar om verksamheten och vilka tjänster som jag tänker mig att företaget ska erbjuda. Därefter letade jag upp ett par lämpliga bilder från [Pixabay](https://pixabay.com/) (logon) och [Unsplash](https://unsplash.com/) (min hero image) genom sökordet "lawyer". Här skapade jag även en favicon genom att välja den kursiva Google-fonten "Niconne", och bara använda A:et (vilket representererar mitt företags namn Advokatkonsulten). Gällande footern så tog jag återigen inspiration från andra sidor vilket slutade med att jag inkluderade en påhittad adress, telefonnummer, mail och sociala ikoner.  Min startsida innehåller sparsamt med text där bilderna tar större plats och där syftet är att leda användaren vidare till rätt sektion. Jag skapade även en highlight-sida med påhittade texter, företag och bilder som jag sökt upp via ovanstående gratis bildtjänster.

## Uppdrag 2 - tema

Mitt tema har skapats från grunden. Här var målet att skapa en känsla av lyx, vilket gjorde att valet av färg föll på något guldaktigt. Jag hittade ett lämpligt monokromatiskt färgtema (för att kunna skapa nyanser för exempelvis knappar och ge tyngd och stabilitet åt dem) på [Adobe Color](https://color.adobe.com/sv/explore) som jag till viss del modifierade. Dessa färger sparade jag som variabler i style.scss där jag importerade övriga scss-filer och där dessa fick representera varje sida för att få en bättre struktur. Därefter letade jag upp en handskriven font "Niconne" på Google Fonts för att ge en mer personlig touch till huvudrubriken. När sidan byggdes upp så hade jag ett papper med designprinciperna och designelementen till hands som jag skrivit ut efter att ha antecknat från litteraturen, och försökte att arbeta utifrån dessa. Eftersom jag ville begränsa antalet fonter så tog jag endast en till kallad "Ubuntu" i sans-serif, vilket jag använder för både rubriker och brödtext. Sans-serif valde jag för att göra lättare att läsa. Min dokumentations-sida gjorde jag bland de sista sakerna i projektet genom att skapa och länka  dokumentation.md och sätta hidden: true i metainformationen.

## Uppdrag 3 - Responsivitet och tillgänglighet

Som huvudsaklig presentation av sidan använde jag mig i huvudsak av grid-attributet (förutom kunder-sidan som använder flex-attributet) med tre kolumner och avstånd mellan dessa genom attributet grid-gap. Exempel på detta är startsidan, presentationen av medarbetare och footern på alla sidor. När jag växlade över till mobil-läge så insåg jag att det behövdes göra justeringar till endast en kolumn. Det gjorde att jag ändrade grid-template-columns till 1fr (en kolumn) istället för 1fr 1fr 1fr (3 kolumner) med hjälp av @media (max-width: 767px). Andra justeringar jag gjorde i mobilt läge var att texten skulle ligga närmare kanten för att få plats med mer text på varje rad. Jag gjorde inga jättestora förändringar med cimage och srcset gällande bildernas pixelstorlek eftersom de redan var bearbetade en del i desktop-läge i och med att de låg tre i bredd. Däremot modifierade jag kvaliteten på filerna beroende på enhet, för att sidan skulle ladda upp snabbare särskilt i mobilt läge. Dessutom gjordes några justeringar med bland annat tabindex och aria-hidden i index.twig-filen för att kunna nå upp till Accessibility 100 i Google Lighthouse. Avslutningsvis så använde jag sidan [Toptal - ColorBlind Web Page Filter](https://www.toptal.com/designers/colorfilter) för att se att sidan fungerade bra även för färgblinda.

## Uppdrag 4 - Alternativt tema (optionellt)

Detta hoppade jag över då jag samtidigt jobbar heltid. Hade jag lagt ner tid på det så skulle jag använt mig av SASS-villkor @if och @else beroende på vilket tema som är aktivt. Mer om detta finns på [sass-lang](https://sass-lang.com/documentation/at-rules/control/if).

## Uppdrag 5 - Analys aktuell Webbplatsdesign

Här valde jag att analysera tre olika svenska industriföretag:
- Assa Abloy
- Volvo
- Metsä Tissue

Jag försökte ta hänsyn till alla tidigare synliga momemt vi pratat om i kursen, det vill säga:
- färg
- typografi
- bilder till viss mån
- designprinciper
- designelement

Däremot tog jag inte med laddningstid för sidorna.
För att få ut färgschemat använde jag mig av [Site Palette](https://chrome.google.com/webstore/detail/site-palette/pekhihjiehdafocefoimckjpbkegknoh?hl=en-GB) och tittade sedan över färgkompositionen genom att jämföra med exempelvis sidan [Tiger Color](https://www.tigercolor.com/color-lab/color-theory/color-harmonies.htm). För att hitta vilken typografi som använts gick jag in i devtools och sökte efter h1, h2 och h3 samt markerade brödtexten. Designprinciperna och designelementen tog jag hjälp av filmerna från Art Heroes rörande [designprinciper](https://www.youtube.com/watch?v=ZK86XQ1iFVs) och [designelement](https://www.youtube.com/watch?v=uVrh3frrC38) samt [ArtOfTeaching](https://www.youtube.com/watch?v=eapeL2fwdc8) och noterade dessa. Därefter försökte jag se över vilka gemensamma nämnare jag kunde hitta på alla sidor innan jag skrev min analystext.

## Uppdrag 6 - Analys Valfri

I analysen av min projektsida valde jag att fokusera på färg och typografi, eftersom dessa är mina kanske mest utmärkande element för sidans framtoning. Jag började med att visualisera mitt färgschema och letade därefter upp en trovärdig källa (Canva) som pratade om vad guldaktig färg förmedlar för intryck. För att studera färgschemat så tog jag [Adobe Color](https://color.adobe.com/sv/create/color-wheel) till hjälp för att få fram att det handlade om ett monokromatiskt färgschema. Fonten och radavståndet för rubrikerna h1-h3 samt brödtexten fick jag fram genom att använda devtools i Firefox, där jag även såg att det var sans-serif. Därefter skrev jag, utifrån de källor vi har haft tillgång på  i kursen, samt ett par till källor jag letat upp som komplement, en analys av sidan. I analysen motiverar jag vad skälen kan vara gällande val av färger och typografi.

## Genomförande av projektet

Jag tyckte detta var ett givande och intressant projekt. Det svåraste är nog att komma igång med allting gällande .htaccess och package.json. Det förekom även vissa svårigheter med nav.css-filen som skrev över det jag hade i style-min.css då den filen läses in efter i index.twig. När jag bytte plats på dem så fungerade inte menyn som den skulle. På vissa ställen i twig-filen fick jag även lägga till klassnamn eftersom scss-filerna annars klagar över att jag använder mig av id som selektor. Jag hade även vissa funderingar hur jag på ett bra sätt skulle kunna gruppera innehållet så att varannan rad färgades mörkgrå och varannan svart för bättre gruppering av innehållet (detta löste jag genom divs med 100% bredd). Men trots vissa problem så har det ändå varit väldigt lärorikt, både gällande scss-kod och hur sidor kan upplevas beroende på vilka färger, element och designprinciper som används. När jag jämför min portfolio-sida med min projektsida så tycker jag mig se en positiv utveckling, även om jag nu inte valde att göra alla moment så är jag ändå mer nöjd med slutresultatet av projektet än med portfolion.

Jag inser att det finns en uppsjö med material att hänvisa till och att det är svårt att få med allt. Tycker ändå att källorna varit bra och ville man ha mer på fötterna så kändes det som man kunde hitta och förstå vad som anses vara lämpliga källor. Handledningen har varit riktigt bra, då Niklas snabbt svarat på frågor som dykt upp i Discord-chatten. Om jag hade önskat något mer från kursen så skulle det nog vara mer kring SASS, villkor och hur det kan användas för att skapa olika designer. På en skala 1-10 så ger jag kursen 8.
