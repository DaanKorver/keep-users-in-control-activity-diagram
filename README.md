# Activity Diagram
<!-- Geef je project een titel en schrijf in één zin wat het is -->
Dit is mijn activity diagram voor het project mijnHVA.

## User Story
Als gebruiker, wil ik een informatiepagina zien, zodat ik antwoord krijg op mijn vraag.

## Activity Diagram
<img src="https://github.com/DaanKorver/keep-users-in-control-activity-diagram/blob/main/assets/Activity%20diagram.png" />

## Uitleg pseudo-code 

Zodra de pagina word geladen word er eerst gekeken of de browser javascript heeft aan staan, zo niet dan komt er een empty state te staan.

Als er wel javascript is dan word de state direct op loading gezet.
Tijdens het laden word de api gefetched doormiddel van getData.
Als er een fout optreed in de api dan word de state op error gezet en gebeurd er niks meer.
Als dit niet het geval is word de data van de api gerenderd en word de state op loaded gezet waarna de applicatie te gebruiken is.


## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
