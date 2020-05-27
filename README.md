# Rob de Groot, Responsive Typography, 2019/2020

## Link naar eindresultaat
<a href="https://grootrob.github.io/web-typography-19-20/closed-captions/index.html">Link naar Eindresultaat</a>
<br>
## Kickoff + Kennismaken Darice
Voor het vak *Web-Typography* bij de Minor Visual Interface Design zijn wij aan de slag gegaan met het vormgeven van *closed-captions* dit is een vorm van ondertiteling waar ook geluiden waardoor verwoord. Deze closed-captions gingen wij ontwerpen voor Darice. Het is daarom van belang dat we Darice goed leerde kennen. Daarom hadden we een kennismakingsgesprejk met haar.
<br>
In de gesprek hebben we haar het hemd van het lijf gevraagd. Van haar lievelingskleur tot haar favoriete blockbuster. Met een flinke lijst op zak ging ik dit prioriteren. De inzichten die ik het belangrijkste vond waren:

1. Kleurgebruik vind ze fijn.
2. Off-screen geluiden visualiseren.
3. Strak en minimalistisch.
4. Kleuren zoals Neon vind ze mooi.
<br>

## Fontkeuze
We hadden de keuze uit het systeemfont of het Brenner font. Ik heb gekozen voor het systeemfont omdat ik dit het meest toegankelijk vindt. Ze loop je niet tegen problemen met het inladen van het font. Ook was de stijl van mijn font niet het meest belangrijk, het maakte dus niet veel uit als er een ander systeemfont gebruikt wordt.

## Exclusive design principles
De **Exclusive design principles** zijn opgesteld door Vasilis van Gemert tijdens zijn studie naar **Inclusive Design principles**. Zijn denkwijze is waarom ontwerpen voor mensen die het web gebruiken zoals wij als je ook specifiek voor één doelgroep of zlefs één persoon kan ontwerpen. Deze principes heb ik als volgt toegepast.

### Study situation
Een belangrijke regel met het ontwerpen voor mensen met een berperking is dat je niet voor ze ontwerpt maar met ze ontwerpt. Pas dan kan je de doelgroep/persoon pas echt goed begrijpen. ZO ook met Darice, closed-captions bestaan al jaren en zijn er voor niet/slecht horende. Maar waarom zijn ze dan nog steeds zo slecht? Dit komt waarschijnlijk omdat er niet samengewerkt wordt met de doelgroep.

Door de gesprekken met Darice ben je haar beter gaan begrijpen en welke wensen ze nou precies heeft. Door de weekelijkse tests heb ik zo mijn werk kunnen aanpassen.

### Ignore conventions
Normaal gesproken word er van je verlangd dat je conventies en patterns gebruiuks om zo alles zo discoverable mogelijk te maken.

Maar door juist het tegenovergestelde te doen creeer je creatievere oplossingen. Zo heb ik er voor gekozen om de geluiden uit te beelden in tekst...Spannend of niet. Maar niet zoals je gewend bent. Door het gebruik van SVG letters rond de video heb ik een frame rond de video gecreeerd. Deze letter hebben elke een animatie die aangeroepen worden wanneer nodig.

### Prioritise identity
Zoals hierboven al genoemd heb ik een aantal van Darice's wensen als hoofd "eisen" gebruikt. Op basis van de eisen ben ik aan de slag gegaan met het ontwerp.

### Add nonsense
De functie is belangrijk maar de ervaring misschien nog wel meer. Door deze nonsense word je ontwerp leuker en creatiever. De nonsense die ik toegevoegd heb is onder andere de verschillende animaties op de tekst. Deze in de hoop dat ze een toevoeging geven aan de ervaring.

# Experiment 1
<img src="/screenshots/Experiment1.png" alt="Experiment1" width="350px">

Voor mijn eerste experiment ben ik aan de gang gegaan met perspectief lijnen. Op deze manier wou ik kunnen laten zien van welke kant het geluid kwam, alsof je in een kamer zat.
In deze vak zou bijvoorbeeld het woord "buzzer" verschijnen (zie afbeelding).

Ook heb ik hier namen toegevoegd aan de closed-caption met een icoon erbij. Hierdoor is het telkens duidelijk wie er praat.

#### Waarom niet gekozen?
Ik ben niet verder gegaan met deze versie omdat het voor Darice niet duidelijk was wta de lijnen waren en het ook erg lastig zal zijn om dit duidelijk te maken. Wel heb ik de nametags in de captions behouden.

# Experiment 2
<img src="/screenshots/Experiment2.png" alt="Experiment2" width="350px">

Voor experiment twee ben ik aan de slag gegaan met neon letters die door een balk heen komen. Op deze manier wou ik geluiden animeren en eventueel pixel figuren toevoegen.

#### Waarom niet gekozen?
Deze versie is het niet geworden omdat Darice snel langs vliegende objecten afleidend vond. Ook werd het snel eentonig en dat vond ik niet creatief genoeg voor deze opdracht.


# Experiment 3 (Eindresultaat)

In de laatste en volledig uitgewerkte versie ben ik gaan experimenteren met geanimeerde worden. Dit keer vliegen ze niet langs maar zitten ze als een soort frame om de video. Met behulp van CSS animatie sheb ik de verschillende woorden en geluiden voorgegeven en op het juist moment ingevoegd.

#### Buzzer
<img src="/screenshots/Buzzer.png" alt="screenshot_van_buzzer-scene" width="350px">

Aan het begin van de video zit al snel een hard buzzer geluid. Bij dit geluid vond ikd e oplichtende letters en trillen niet genoeg. Daarom hebik ook een border en width tranformatie toegevoed op de video. Deze heeft dit moment net een beetje extra effect.

#### Cells
<img src="/screenshots/Cells.png" alt="screenshot_van_cells-scene" width="350px">

Omdat het met de captions niet altijd duidelijk was hoe vaak een woord gezeg werd (en dat werden sommige woorden nogal vaak) heb ik de **Cells** toegevoegd aan de geluiden. Op deze manier kan je precies zien wanneer het woord gezegd wordt en of het herhaald wordt.


#### Interlinked
<img src="/screenshots/Interlinked.png" alt="screenshot_van_Interlinked-scene" width="350px">

Net als de **Cells** werd het woord **Interlinked** ook erg vaak herhaald ook deze worden lichten één voor één op. In dit geval heb ik ze in elkaar laten gaan om het interlinked effect sterker te maken. Ook zit er een blend mode op om eenbgaaf kleur effect te creeeren wanneer ze overlappen.

#### Dramatic Music
<img src="/screenshots/Dramatic.png" alt="screenshot_van_Dramatic_music-scene" width="350px">

De **Dramatic Music** teksts blijf maar liefst 45 seconden in beeld en pulseert langzaam om het niet afleidend te maken maar toch duidelijk te maken dat de muziek nog steeds speelt. Hetzelfde geldt voor de **Intensifies** tekst deze gaat steeds meer licht geven om duidelijk te maken dat de scene steeds heftiger wordt.

