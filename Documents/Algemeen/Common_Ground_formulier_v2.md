# Aanmeld formulier mini fieldlab Common Grond

Beste deelnemer,

Op 11 en 12 maart werken we twee dagen met alle Common Ground teams samen in de Fabrique in Utrecht. Op 13 maart demonstreren de teams hun voortgang tijdens het Congrestival van de VNG.

Met Common Ground werken gemeenten en andere organisaties samen aan betere, veiligere en wendbaardere dienstverlening en operatie. Dit doen we aan de hand van gezamenlijke principes en een moderne way of working. Over deze principes is een aantal documenten opgesteld; in het bijzonder de Common Ground Informatiearchitectuurprincipes en Common Ground Realisatieprincipes zijn zeer belangrijk om in de projectplanning en oplossingsarchitectuur toe te passen. Ook het gesprek over en vergelijking van voorgestelde oplossingen baseren we op deze principes. 

Deze documenten zijn te vinden op https://www.gemmaonline.nl/index.php/Thema_Samen_organiseren 

Om een goed overzicht te creëren van waar alle teams aan werken, zowel voor de teams onderling als voor bezoekers van het Congrestival, vragen we je om:
* Bijgaande vragenlijst in te vullen en aan ons terug te sturen. 
* Een architectuurplaat aan te leveren van de oplossing die ontwikkeld wordt, geplot op het vijf lagen model (zie vraag B6).
* Eventuele andere projectinformatie die je graag wilt delen (bijvoorbeeld projectplan).

Bij vragen of problemen helpen we graag!

# A Projectinformatie
## A1 Projecttitel
Convenant Gemeenten – Trouw applicatie

## A2 Deelnemende organisaties
VNG Realisatie, Gemeenten Almere, Amsterdam, Drechterland, Enkhuizen, Haarlem, Heereveen, Hoorn, Koggeland, Medemblik, Opmeer, Stede Broec en Zaanstad. Gemeente Utrecht en Eindhoven zijn een soort gelijke traject eerder gestart, beide partijen zullen elkaar op de hoogte houden en helpen. 

## A3 Contactpersonen
* Product Owner - Km Engel - kim.engel@medemblik.n
* Scrum Master - Jan Willem Kooi - jan.willem.kooi@sltn.nl

## A4 Lead developer of architect
* Lead developer Front -  Stefan Woudstra  - s.woudstra@heerenveen.nl
* Lead developer Back - Thijs Broersen - t.broersen@hoorn.nl
* Lead architect - Bas de Boer - bdeboer@haarlem.nl
* Lead Proces – Daphne de Bruijn - dadebruijn@almere.nl 


## A5 Korte omschrijving van het project
We ontwikkelen een set aan generieke tools waarmee gemeenten hun inwoners in staat kunnen stellen om, in standaardsituaties, hun huwelijk zoveel mogelijk digitaal te regelen. Dit doen we gebaseerd op de principes van Common Ground en ontwikkellen met Open Source Software. Het doel is dat we het project zo afronden, dat er met een generieke API aangesloten kan worden op een eigen front-end. Voor het presenteren ontwikkelen wij een eigen demo front-end.  

## A6 Wat is de looptijd/globale planning van het gehele project (inclusief belangrijke deadlines) en welke rol speelt 11, 2,13 maart daarin?

* Ma 11 Mrt 19 – Team komt bij elkaar om samen te ontwikkelen
* Wo 13 Mrt 19 – Lopende presentaties houden op demomarkt van VNG congres; Pronken, kijken wat mensen van het project vinden en informatie ophalen bij geïnteresseerde. 
* Do 14 Mrt 19 – Einde sprint 2 Retrospectieve, demo & planning sprint 3
* Wo 10 Apr 19 - Einde sprint 3 Retrospectieve, demo & planning sprint 4
* Eventuele verdere planning bekijken we bij eind sprint 3

# B Inhoudelijke doelen 11,12,13 maart
## B1 Welk tastbaar resultaat wil je laten zien op 13 maart?
*Voorbeeld: ter vervanging van een silo-product worden twee componenten ontwikkeld die via NLX communiceren*

* Demo  front-end, qua hoever we nu zijn 
* Resultaten van proces onderzoek
* Toepassing Common ground
* Aanpak Samenwerking en samenstelling; hoe we het tot nu toe gedaan hebben en verder willen gaan aanpakken

## B2 Waar ga je op 11 en 12 maart aan werken?
*Voorbeeld: Implementatie van het benodigde formulier en koppeling via NLX*

Wij gaan samen ontwikkelen, er zal een deel bezig zijn met mock-ups en proces omschrijving, ander deel zal zich buigen over de data en back-end. 

## B3 Hoe maakt het project gebruik van, of draagt het bij aan de verwezenlijking van de Common Ground principes ?
*Voorbeeld: we scheiden data en interactie en proces in afzonderlijke componenten, 
die voor andere gemeenten herbruikbaar zijn*

Wij verplichten onszelf om alle Common Ground principes te gebruiken. Dit is een van de redenen van dit project.

## B4 Welke bestaande componenten wil je gaan hergebruiken?
*Voorbeeld: Inschrijfformulier: omschrijving, NLX-inway/outway, API: omschrijving*

NLX, Camunda (BPMn /DMN) voor de proceslaag, bestaande ‘Trouw’ APIs van de 3 BRP-leveranciers

## B5 Welke componenten worden nieuw ontwikkeld?
*Voorbeeld: Inschrijfformulier: omschrijving, API voor inschrijvingen: omschrijving*

IM model Trouwen op basis van de beschikbare ‘trouw’ apis en het komen tot een ‘trouw standaard’. Ontwerpen van proces en business logica en deze middels APIs ontsluiten naar de front-end.

## B6 Kun je een plaatje aanleveren van de oplossingsarchitectuur geplot op het vijf-lagen model ?
![5 lagen model Common Ground](/Documents/Architectuur/img/5lagen.png?raw=true)





