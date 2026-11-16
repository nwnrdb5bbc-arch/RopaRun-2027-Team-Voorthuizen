INTERACTIEVE SPONSORKAART - ROPARUN 2027

INHOUD
- index.html: de interactieve kaart met 558 vaste routepunten.
- donated-kilometers.json: bepaalt uitsluitend welke kilometerbolletjes rood zijn.

PUBLICEREN OP GITHUB PAGES
1. Upload index.html en donated-kilometers.json naar dezelfde map in de GitHub-repository.
2. Zorg dat het HTML-bestand index.html heet.
3. Activeer GitHub Pages voor de branch en map waarin deze bestanden staan.

EEN KILOMETER ROOD MAKEN
Open donated-kilometers.json en voeg het kilometernummer toe aan de lijst "gedoneerd".

Voorbeeld:
{
  "uitleg": "Pas alleen de lijst gedoneerd aan. De route en GPS-locaties staan in index.html en veranderen hierdoor niet.",
  "gedoneerd": [12, 45, 103]
}

In dit voorbeeld worden kilometer 12, 45 en 103 rood. Alle andere bolletjes blijven groen.

BELANGRIJK
- Wijzig voor de donatiestatus alleen donated-kilometers.json.
- De route en GPS-locaties staan vast in index.html en blijven ongewijzigd.
- Beide bestanden moeten in dezelfde map staan.
- Open de kaart via GitHub Pages of een andere webserver. Bij rechtstreeks openen vanaf de computer kan de browser het JSON-bestand blokkeren vanwege beveiligingsregels.
- Groene bolletjes verwijzen naar het Microsoft Forms-formulier.
