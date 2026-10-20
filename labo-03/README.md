# Labo 3 - reflecties

Naam: Emile Vercammen

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
> Margin en padding op 0, je kon deze aflezen in de Developer Tools van je browser.
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
> Als je het browservenster hoger maakt, worden de banden ook hoger, omdat hun hoogte ingesteld is op 20vh. vh is een eenheid die gebaseerd is op de hoogte van het browservenster. Wat niet verandert, zijn de kleuren en de verhouding: elke band blijft  20% van de vensterhoogte innemen.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
> text-align centreerde de tekst, margin centreerde de kolom horizontaal. De waarde auto verdeelt de overblijvende horizontale ruimte links en rechts, terwijl 12rem ruimte bovenaan geeft en 0 ruimte onderaan geeft.
- Waarom werkte de padding op de knop pas na `display: inline-block`?
> Een link (a) is standaard een inline-element. Bij inline-elementen werkt het boxmodel niet op dezelfde manier als bij block-elementen, vooral voor de verticale afmetingen. Met display: inline-block; gedraagt de link zich als een blokje op dezelfde tekstregel. Daardoor zal de padding niet overlappen met de tekstregel erboven en duwt zichzelf weg van de andere elementen.

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?
> De visuele breedte van het tabblad is exact 15rem, omdat reset.css de eigenschap box-sizing: border-box; instelt voor alle elementen. In stijl.css staat width: 15rem;. Door box-sizing: border-box omvat die breedte de volledige box: de inhoud, de padding en de border. De padding van 1rem 2rem en de border van 0.25rem komen dus niet boven op de 15rem. Ze nemen ruimte in binnen de totale breedte.
Als box-sizing: border-box niet ingesteld was, zou de standaardwaarde content-box gelden. Dan zou de width: 15rem alleen de inhoud bepalen, en zou den de padding en de border erbij worden opgeteld. De totale breedte zou dan groter zijn dan 15rem.
Daarom is het tabblad exact 15rem breed.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
> Omdat main een hoogte heeft van 90vh. De cirkel kan dus 70% van de hoogte van main gebruiken.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
> Op de breedte van de ouder (main), ook voor de boven- en ondermarge. (Met auto erachter wil dat zeggen dat de resterende horizontale ruimte wordt verdeeld.)

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
> Een min-height, omdat het minstens 80% van de viewport-height moet innemen.
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
> De helft gaat verticaal staan tegenover de eerste helft, in plaats van naast de eerste helft horizontaal.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
