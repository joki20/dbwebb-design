---
Title: Om
Description: Min Om-sida.
---

# Om

Den här hemsidan är uppbyggd med hjälp av teknikerna:
- **Pico**: CMS-ramverk för att bygga upp hela sidans struktur
- **Cygwin**: Terminal för att skapa mappar, filer och ladda hem paket genom Node.
- **Node.js**: JavaScript-miljö med möjlighet att ladda hem paket genom npm (SASS, stylelint, normalize, Font Awesome). Paketen kommer ligga i package.json
- **SASS (.scss)**: Preprocessor med variabler, nesting, funktioner med mera för att generera CSS. Gör om till CSS mha npm run style inuti mappen /themes . Glöm inte ändra till rätt tema i package.json på rad 9 och 10 (fyra ställen)
- **stylelint**: Validerar vår .scss-kod mha npm run lint eller dbwebb validate
- **normalize.css**: SASS-modul för att normalisera stilar över browsers
- **Font Awesome**: SASS-modul med ett bibliotek av ikoner
- **Google Fonts**: Gratis fonter och ikoner på nätet
- **media queries**: Anpassar sidans stil till mobila format
