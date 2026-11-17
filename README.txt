INTERACTIEVE SPONSORKAART - ROPARUN 2027 - v2.3

Nieuw:
- Rode kilometer toont naam van donateur.
- Rode kilometer toont de achtergelaten boodschap voor Team Voorthuizen.
- Zoekbalk, mobiele kaartweergave, Forms-link en vaste route blijven behouden.

JSON voorbeeld:
{
  "donaties": [
    {"km": 12, "naam": "Voorbeeld donateur", "boodschap": "Heel veel succes Team Voorthuizen!"},
    {"km": 45, "naam": "Familie De Vries", "boodschap": "Zet hem op!"}
  ]
}

Een kilometer in de lijst donaties wordt rood. Naam en boodschap verschijnen in de popup. Laat persoonsgegevens en boodschappen alleen publiek zien wanneer dit passend is en de donateur hiermee akkoord is.

Publiceren:
Plaats index.html en donated-kilometers.json in dezelfde GitHub Pages-map. Test bij voorkeur eerst in de testbranch.
