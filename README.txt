INTERACTIEVE SPONSORKAART - ROPARUN 2027 - v2.1

INHOUD
- index.html: interactieve kaart met 558 vaste routepunten en kilometerzoekfunctie.
- donated-kilometers.json: bepaalt alleen welke kilometerbolletjes rood zijn.
- README.txt: deze uitleg.

WIJZIGINGEN IN v2.1
- De kaart zoomt bij openen uit naar de volledige route.
- Er is extra ruimte aan de linkerkant zodat het informatiepaneel de route minder afdekt.
- Zoekbalk toegevoegd: voer een kilometer van 0 t/m 557 in en klik op Zoek.
- De kaart zoomt naar het kilometerpunt en opent de popup.

PUBLICEREN OP GITHUB PAGES
1. Upload index.html en donated-kilometers.json naar dezelfde map.
2. Vervang de bestaande index.html door deze nieuwe versie.
3. Laat donated-kilometers.json naast index.html staan.

DONATIESTATUS
Pas uitsluitend de lijst "gedoneerd" in donated-kilometers.json aan. Voorbeeld:
{
  "uitleg": "Pas alleen de lijst gedoneerd aan. De route en GPS-locaties staan in index.html en veranderen hierdoor niet.",
  "gedoneerd": [12, 45, 103]
}

Groen = beschikbaar. Rood = gedoneerd. De route en GPS-locaties veranderen niet door de JSON.
