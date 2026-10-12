# Labo 2 - reflecties

Naam: Emile Vercammen

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: elke link in de header binnen de navigatie en in een list-item die kind zijn van unordered-list
- b. `article > p`: alleen paragrafen die direct kind zijn van een ul
- c. `.uren li:nth-child(3)`: het 3de list-item met class uren 
- d. `h2 ~ p`: alle paragrafen die na een h2-element staan en dezelfde ouder hebben
- e. `.rassen li:first-child`: het eerste list-item van class rassen

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|----|------|---------------|----|----|
| 1  | G    | herkomst      | G  | y  |
| 2  | B    | volgorde      | B  | y  |
| 3  | R    | specificiteit | R  | y  |
| 4  | GREY | herkomst      | R  | n  |
| 5  | R    | specificiteit | B  | y  |
| 6  | B    | specificiteit | B  | y  |
| 7  | GREY | herkomst      | R  | n  |
| 8  | B    | specificiteit | B  | y  |
| 9  | R    | specificiteit | R  | y  |
| 10 | G    | specificiteit | G  | y  |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
> De kleur, overerving doorheen het document.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
> nav a, omdat deze al verwijst naar de links in nav.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
> Wanneer de link-tekst (van a in de footer) grijs moest maken zonder hover of focus. Ik moest extra verduidelijken aan de hand van de selector "footer a" om de kleur van de link-tekst aan te kunnen passen.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
> --color-accent: #ffbf00;, --color-gedempt: #6b6b6b;, --lettertype: Arial;
--> omdat deze de kleuren doorheen heel het document in de body van elke pagina aanpast (accent voor belangrijke tekst, gedempt voor footer)
--> om het type tekst in 1 regel bovenaan in root van de stylesheet aan te passen voor alle HTML-pagina's
- Wat verandert er in je site als je één token wijzigt?
> de kleur, het teksttype of de standaardmaat wordt gewijzigd doorheen elke HTML-pagina gelinkt aan de stylesheet

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
