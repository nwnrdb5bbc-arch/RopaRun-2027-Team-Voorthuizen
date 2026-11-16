INTERACTIEVE SPONSORKAART - ROPARUN 2027 - v2.2

INHOUD
- index.html: interactieve kaart met 558 vaste routepunten en kilometerzoekfunctie.
- donated-kilometers.json: bepaalt welke kilometerbolletjes rood zijn en bevat donateurgegevens.
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
1. Plaats donated-kilometers.json in exact dezelfde map als index.html.
2. Laat de bestandsnamen ongewijzigd.
3. Wacht na een wijziging doorgaans 1 tot 3 minuten op GitHub Pages.
4. Vernieuw daarna met Ctrl+F5 op Windows of wis de browsercache op mobiel.

DONATIESTATUS EN DONATEURGEGEVENS AANPASSEN
- Voeg het kilometernummer toe aan de lijst "gedoneerd" om het punt rood te maken.
- Vul voor die kilometer ook "naam" en/of "boodschap" in bij "donateurs".
- Gebruik het kilometernummer als tekstsleutel in "donateurs".
- Laat "naam" leeg als de donateur anoniem wil blijven; laat "boodschap" leeg als er geen boodschap is.

Voorbeeld:
{
  "uitleg": "Pas gedoneerd en donateurs aan.",
  "gedoneerd": [12, 45],
  "donateurs": {
    "12": {
      "naam": "Voorbeeldnaam",
      "boodschap": "Succes met de RopaRun, team Voorthuizen!"
    },
    "45": {
      "naam": "",
      "boodschap": "Veel succes!"
    }
  }
}

Let op: de huidige kaart gebruikt "gedoneerd" om de punten rood te kleuren. De naam en boodschap staan nu in het JSON-bestand; om ze ook in de popup op de kaart te tonen, moet index.html hiervoor nog worden aangepast.
Groen = beschikbaar.
Rood = gedoneerd.
De route en GPS-locaties blijven ongewijzigd.
