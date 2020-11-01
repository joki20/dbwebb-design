---
Title: Kmom01
Description: Min sida för kmom01.
---

# Kmom01

Har precis gjort klart kmom01. När jag tänker på CMS är det WordPress i första hand jag kan relatera till. Miljön i WordPress är dock mer handledande och upplagd för alltifrån nybörjare till experter. Pico i sin tur kan ge dig större friheter då du har mer kontroll gällande att implementera sin egen kod. Det kan dock kräva att man är någorlunda rutinerad inom programmeringsvärlden.

Vissa saker inom PHP i filen dyker upp som jag inte är bekant med. Det gäller exempelvis användningen av procenttecken som vid {% endfor %} och att dubbla måsvingar gör en utskrift. Sedan har vi andra okända filer som config.yml, index.twig och .htaccess, likaså nya attribut som aria-hidden. Just nu känns det som att det är så mycket nytt att det går inte att förstå allt, utan man försöker hänga med i "flödet".

Svårast av allt för egen del var att hantera GitHub via CygWin. Det blev många frågor till kursledaren innan jag fick det att gå ihop. Är lite orolig att det här kommer att stjälpa mig. Tyvärr är det också väldigt mycket text i förklaringarna till Git, så jag anser att det blir svårare än vad det eventuellt behöver bli. Ni kanske borde ha någon sammanfattande sida om hur man hanterar Git?

Gällande design och användbarhet så är det viktigt med en god design för att ge ett gott första intryck. Användbarheten i sin tur handlar mer om att tillgängliggöra sidan för olika slags människor. Det ska exempelvis gå att tabba sig runt på sidan på ett förutseende sätt (exempelvis gällande menyvalen), och kontrasterna mellan bakgrund- och förgrundsfärg måste vara tillräckligt skarpa. Bilder bör även ha tydliga alt-texter ifall de inte går att ladda av någon anledning, så man vet vad bilden innehåller.

Det var kul att styla sin sida. I och med att man använder normalize så inser man att webbläsarna fixar mycket åt oss gratis. Nu fick jag exempelvis själv bestämma avståndet mellan paragrafer och marginaler från bilder. Men det är fördelaktigt på det sättet att alla webbläsare då får en liknande stil och att det inte skiljer sig så mycket mellan dem för en webbsida.

Det som jag hade mest problem med var att få till min flashbild, att den inte skulle ta upp så mycket plats. Jag löste detta genom att sätta specificera höjden på bilden samt göra bredden till 100% och ta bort marginalerna. Menyn fick jag också problem med då den "växte" nedanför bilden, vilket jag fick lösa genom flex: 0 0 auto där första nollan inte tillåter att menyn växer (flex-grow).

Det jag tar med mig från detta kursmoment är att jag behöver jobba mycket mera med framförallt GitHub och förstå hur man hanterar det. Jag inser vikten av att samarbeta med verktyget och att det efterfrågas i arbetslivet, även om det inte är helt lätt att komma in i såhär i början.
