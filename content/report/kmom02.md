---
Title: Kmom02
Description: Min sida för kmom02.
---

# Kmom02

Jag har lagt till variabler och använt mig av nästlade selektorer i min SASS-kod för temat kmom02 (fyndigt temanamn...). Kan se en fördel i att inte behöva upprepa kod för att ange färg, och bara ändra på ett ställe i koden. Gällandes nästling skapas en mapp-liknande struktur vilket kan göra koden mer överblickbar i slutändan.

Gällandes Node och npm så har jag provat på det lite sedan tidigare för att försöka skapa sidor i React. Det positiva är ju att det finns många färdiga bibliotek man kan ladda hem och implementera på sin sida. Nackdelen enligt mig är att du lämnar över kontrollen och att mycket går på automatik, vilket kan förta känslan av att ha gjort något själv. På så sätt är jag lite kluven.

Jag glömde först ändra i package.json till mitt tema, vilket gjorde att jag skrev över mitt gamla tema (joki20) vid kompileringen till CSS. Att behöva kompilera blir ett extra steg innan man kan se sin färdiga kod och det gillar jag inte riktigt jämfört med att använda ordinarie CSS direkt från början.

Gällandes temat så utgick jag från min valda flash-img där jag använde en color picker för att plocka ut färger därifrån. Tanken var att försöka få det att se mer enhetligt ut. Framöver så kanske jag använder mig av [Adobe Color Picker](https://color.adobe.com/) istället för detta ändamål, en sida som innehåller en stor mängd olika färgteman.

I övrigt gjorde jag småjusteringar gällande responsiviteten, exempelvis centrerade jag alla headers, kmom-länkar och bilder i mobilt läge. På små skärmar ser det bättre ut än om sakerna ligger på sidan. Jag ökade även radavståndet till 1.4 för att få lite luftigare text och göra det mer lättläst.

För saker som kunde appliceras på alla kommande teman lade jag scss-kod i filen shared/scss/layout.scss. Detta gällde exempelvis
- höjden på flash-bilden och tillhörande ram
- min-height på containern för sidor med inte så mycket text (som redovisningssidan)
- bildernas utseende och storlek
- footerns bredd
- med mera...

Jag försökte att särskilja ovanstående från sådant som skulle vara unikt för temat. Det unika lade jag därför i temats scss-fil.

Det jag tar med mig från detta kursmoment är, precis som jag tog upp här innan, möjligheten att kunna ladda hem och använda färdiga paket för att skapa sidor. Även att SCSS underlättar för oss att skapa en strukturerad styling och att undvika DRY-kod.
