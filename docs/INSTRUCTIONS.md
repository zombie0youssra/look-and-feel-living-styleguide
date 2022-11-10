
# Look and Feel - Living Styleguide

Ontwerp en maak een *living styleguide* voor een opdrachtgever.

## Context

Deze deeltaak hoort bij sprint 4 Look and Feel. Dit is een deeltaak die je in een team uitvoert, namelijk alle studenten die een project voor dezelfde opdrachtgever doen.

In de workshop Living Styleguide wordt uitgelegd wat een living styleguide is en wat het nut ervan is.


## Doel van deze opdracht

> Living style guides are an important tool for web development today, especially in large, complex web applications. They help document styles and patterns, keep designers and developers in sync, and greatly help to organize and distill complex interfaces. (<cite>[Lambert, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/))

Een living styleguide is essentieel voor het begrijpen en overbrengen van de look and feel van een website. Het geeft een gedeeld begrip van alle teamleden over hoe iets eruit moet zien en hoe markup (HTML) en vormgeving (CSS) moeten worden toegepast. Een living styleguide helpt bij het ontwerpen en bouwen van een website met consistente look and feel in de huisstijl van een opdrachtgever.

## Werkwijze

Deze opdracht gaat over [analyseren](#analyseren) en [ontwerpen](#ontwerpen) van de DLC. In de analysefase breng je door het doen van een *interface audit* in kaart hoe het zit met de consistentie van de huidige uitingen van de opdrachtgever en welke huisstijl elementen in gebruik zijn. Het resultaat is een *interface inventory*. In de ontwerpfase maak je keuzes, bepaal je ontwerp standaarden en leg je vast hoe componenten in HTML en CSS opgenomen worden. 

Het resultaat is een levende - dat wil zeggen live, semantisch, toegankelijk en responsive - stijlgids welke gebruikt kan worden door alle frontenders in een organisatie. Welke kleuren en typografie worden gebruikt in de huisstijl? Wat zijn overeenkomstige elementen van de verschillende pagina's of componenten? Hoe ziet de layout van verschillende onderdelen eruit? Hoe gedraagt de website zich in verschillende contexten (responsive design). En tenslotte, welke HTML en CSS is nodig om de elementen van de living styleguide op te maken en vorm te geven?

### Analyseren

Je begint met het uitvoeren van een *interface audit* waarin je een gecategoriseerde opsomming maakt van de componenten waaruit jouw website, app, intranet, hatseflats of whatever opgebouwd is. Het resultaat van de audit is een *interface inventory*, een verzameling van alle atomen, moleculen en organismen van een interface.

Een *interface inventory* is een goed middel om een opdrachtgever of werkgever over te halen om extra tijd uit te trekken voor het vastleggen van een solide ontwerpsysteem. Het maken van een living-styleguide is een goed idee voor het consistent toepassen van een huisstijl, maar het kost wel tijd om er een te ontwikkelen. Het laten zien van inconsistentie door middel van een interface inventory kan overtuigend werken.

**N.B: Jullie voeren de interface audit uit op alle gemaakte projecten voor de opdrachtgever. Dus kies de oorspronkelijke huisstijl én alle uitgewerkte user-stories!**

#### Voer een interface audit uit:
 
 1. **Open het project.** Zorg dat je weet hoe je specifieke screenshots moet maken (een selectie en niet je hele scherm).
 2. **Zet een blanco template op.** Hier dump en categoriseer je de componenten van de interface. Keynote of PowerPoint werken prima, alles wat je nodig hebt zijn een categorie titel en een plek om screenshots te dumpen.
 3. **Begin met screenshotten.** Nu het leuke gedeelte. Neem screenshots van de ingrediënten van jouw interface. Je doel is om unieke versies van componenten te vangen. Hier een mogelijke categorisering (kies wat van toepassing is op jouw project!):
    - Globals: header, footer en andere globale elementen
    - Navigatie: primair, footer, paginering, kruimelpad, …
    - Afbeeldingen: logo’s, hero’s, avatars, thumbnails, …
    - Iconen: vergrootglas, sociale, spinners, favicons, hamburgers, pijlen, …
    - Formulieren: inputs, textareas, select menu’s, checkboxes, radio buttons, …
    - Knoppen: groot, klein, primair, secundair, voortgang, …
    - Interactieve componenten: accordions, tabs, carrousels, alles met bewegende delen
    - Media: video spelers, audio spelers, …
    - Berichtgeving: alerts, success, error, warning, validatie, …
    - Headings: h1, h2, h3, h4, h5, h6 en typografische variaties
    - Lijsten: ongeordend, geordend, definitielijst, bullets, lijnen, …
    - 3de partij: widgets, iframes, beurs-tickets, social links, alles wat niet op hetzelfde domein gehost wordt
    - Reclame: reclame banners en andere reclame elementen
    - Blokken: combinaties van afbeeldingen, koppen en inleidingen, …
    - Animatie: gifjes van interface animatie of echt werkende animaties
    - Kleuren: unieke huisstijlkleuren
    - …
4. **Categoriseer jouw screenshots.** Je kunt dit doen terwijl je bezig bent of na afloop van je screenshot sessie. Het doel is dat je alle verschillende voorkomens van een bepaald molecuul naast elkaar kunt zien.
5. **Presenteer.** Laat als groep de interface inventory zien aan je ~~opdrachtgever~~ docent en kijk toe hoe ze in tranen uitbarsten. Na deze exercitie ga je door met [ontwerpen](#ontwerpen).

#### Meer lezen?

- [Brad Frost, Interface Inventory, 2013](https://bradfrost.com/blog/post/interface-inventory/)
- [Laure Gabrielle Chatenet, Ousama Jaâfour, How to create an interface inventory? 2017](https://capian.co/blog/interface-inventory/)
- [Mar High, How to create an interface inventory, 2021](https://mainmatter.com/blog/2021/06/02/how-to-create-an-interface-inventory/)
- [Brad Frost, Atomic Design, 2013](https://bradfrost.com/blog/post/atomic-web-design/)

### Ontwerpen

- Kijk of je bij de website van de opdrachtgever een HTML en CSS strategie kan ontdekken
- Maak afspraken over HTML structuur & semantiek en CSS
- Maak afspraken over de naamgeving van classes en id's
- Maak een styleguide webpagina met HTML en CSS

#### Meer lezen?

- [Steven Lambert, Creating A Living Style Guide, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/)

## Criteria

Focus sprint 4 - De focus van deze sprint ligt op het toepassen van een huisstijl en het maken van formulieren.

Deze deeltaak hoort bij het gedragscriterium:  

Samenwerken: Draagt verantwoording voor eigen resultaten en verwerkt ontvangen feedback

Deze opdracht is done als je:

- [ ] een Interface Inventory hebt opgenomen in de wiki
- [ ] de analyse van de HTML en CSS van de bestaande website hebt gedocumenteerd in de wiki
- [ ] afspraken over HTML, CSS en naamgeving hebt gedocumenteerd in de wiki
- [ ] een opzet van de living styleguide hebt gemaakt met HTML en CSS
- [ ] de living styleguide te bekijken is via Github pages

