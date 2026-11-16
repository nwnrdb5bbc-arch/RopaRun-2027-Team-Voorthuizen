INTERACTIEVE SPONSORKAART - ROPARUN 2027 - v2.2

INHOUD
- index.html: interactieve kaart met 558 vaste routepunten en kilometerzoekfunctie.
- donated-kilometers.json: bepaalt alleen welke kilometerbolletjes rood zijn.
- README.txt: deze uitleg.

OPGELOST IN v2.2
- Probleem met verspreide kaarttegels en grote witte vlakken opgelost.
- Leaflet wordt nu via jsDelivr geladen zonder integrity-blokkering.
- Kritieke Leaflet-opmaak staat ook in index.html als extra beveiliging.
- De kaart gebruikt altijd 100% van het browservenster.
- De volledige route wordt na het laden opnieuw passend in beeld gezet.
- De vaste linkermarge van 190 pixels is verwijderd.
- Mobiele weergave en kilometerzoekfunctie zijn behouden en verbeterd.

PUBLICEREN OP GITHUB PAGES
1. Verwijder of vervang de bestaande index.html in de GitHub-repository.
2. Upload de index.html uit dit pakket.
3. Plaats donated-kilometers.json in exact dezelfde map als index.html.
4. Laat de bestandsnamen ongewijzigd.
5. Wacht na uploaden doorgaans 1 tot 3 minuten op GitHub Pages.
6. Vernieuw daarna met Ctrl+F5 op Windows of wis de browsercache op mobiel.

DONATIESTATUS AANPASSEN
Pas alleen de lijst "gedoneerd" in donated-kilometers.json aan, bijvoorbeeld:
{
  "uitleg": "Pas alleen de lijst gedoneerd aan. De route en GPS-locaties staan in index.html en veranderen hierdoor niet.",
  "gedoneerd": [12, 45, 103]
}

Groen = beschikbaar.
Rood = gedoneerd.
De route en GPS-locaties blijven ongewijzigd.
