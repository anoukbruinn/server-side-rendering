> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel
<!-- Plantswap -->

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Gebruik](#gebruik)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Ik heb een website gemaakt voor Buurtcampus oost. Op deze website kun je voor plantswap een stekje reserveren en hier meer informatie over vinden.
Deze website heb ik gemaakt vanwege een opdracht voor de opdrachtgever: we hebben 3 userstories gekregen en vanuit hieruit moesten we gaan werken. 

### Userstories

- Als buurtbewoner van Amsterdam Oost wil ik informatie vinden over het verzorgen van planten, zodat ik niet steeds nieuwe planten hoef te kopen en daarme verspilling tegen ga.
- Als buurtbewoner van Amsterdam Oost wil ik informatie vinden over de positieve bijdrage van planten op de leefomgeving, zodat ik gemotiveerd raak stekjes te planten in mijn omgeving
- Als buurtbewoner van Amsterdam Oost wil ik kunnen zien welke stekjes momenteel in de stekjeskast zitten, zodat ik kan overwegen een stekje om te ruilen

![MacBook Air - 1 (2)](https://user-images.githubusercontent.com/112856687/225868928-38a52cc6-fced-484e-94f8-285c1bdbd2b2.png)


## Kenmerken

Ik heb voor dit project gebruik gemaakt van: Json, Ejs, Js, CSS en Html. Het belangrijkste wat ik heb gedaan in de Javascript is verwijzen naar de API.
Dit heb ik op deze manier gedaan.

`const url = 'https://api.buurtcampus-oost.fdnd.nl/api/v1/stekjes?first=1000'
const data = await fetch(url).then((response) => response.json())`

### tools
- figma
- visuel studio code
- Terminal
- Npm
- nodejs
- josn
### gerbuikte technieken
- node
- javascript
- ejs
- html
- css

<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

## Installatie

1: Om in de repository te werken en aanpassingen te maken moet je node.js downloaden versie: <br> 
2: Clone of download deze respository. <br>
3: Open hem in je code-editor. <br>
4: open de terminal en type npm install. <br>
5: Daarna door gerbruik van npm start krijg je een localhost link waar je de code live ziet. <br>
6: Live zetten van je project kan met behulp van cyclic. 

## Gebruik

## Bronnen

### de bronnen die zijn gebruikt voor dit project zijn:

https://nodejs.org/en
https://ejs.co/

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
