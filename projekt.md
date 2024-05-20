# Kortleken
Skriv ett program med JavaScript som simulerar en kortlek.

## Beskrivning
Vi utgår från en vanlig kortlek.

**Deluppgift 1**: först ska programmet skriva ut namnet på alla spelkort. Exempel: 'ruter ess', 'spader 7', 'hjärter kung' osv.

**Deluppgift 2**: programmet ska dra två spelkort och tala om vilka de är.

**Deluppgift 3**: programmet ska tala om vilken den bästa poker-kombinationen är.
1. Om korten har samma valör är det *par*
2. Om korten har olika valör gäller *kortet med högst värde* (obs, ess räknas som höst)

**Level up**:
+ Utöka programmet successivt så att det räknar med först 3, sedan 4 och sist 5 kort. [Poker-händer på wikipedia](https://en.wikipedia.org/wiki/List_of_poker_hands)

+ Dra två olika händer efter varandra och tala om vilken av dem som vinner

## Resurser

Lägg till den här koden i din js-fil:
```js
function slumpa(from, to) {
	return Math.floor( Math.random() * (to + 1 - from) ) + from
}
```

Nu kan du använda den för att slumpa ett tal, så här:
```js
let x = slumpa(1, 13)
```


## Inlämning
Din inlämning ska vara något av följande:
+ en länk till din [replit](https://replit.com/)
+ en länk till GitHub Gist
+ en js-fil

Länk till inlämningen hittar du [här](README.md)
