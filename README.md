# Online sfeerviering Kerst

Interactieve kerstviering in een 3D-woonkamer, voor tablet, laptop en groot scherm. Je kiest op het startscherm **Start sfeerviering** (geleid, stap voor stap) of **Zelf rondkijken**.

De viering: klok, *Vrede voor jou*, kaars aansteken, welkomslied (voor 1 tot 10 mensen), *Komt allen tezamen*, het kerstverhaal bij de stal, *De herdertjes lagen bij nachte*, gebed, Onze Vader, zegenlied en de kaars uitblazen.

## Bestanden

| Pad | Inhoud |
|---|---|
| `index.html` | de hele website (three.js en de kamer zitten erin) |
| `pano-avond.js` | de kamer in kerstavondlicht, vooraf gerenderd |
| `muziek/` | de liedjes |
| `stem/kerst/` | de ingesproken tekst |
| `video/kerstverhaal.mp4` | het kerstverhaal |

Er is geen bouwstap: de map wordt zoals hij is als statische website gepubliceerd (Vercel).

## Lokaal bekijken

Start in deze map een eenvoudige webserver, bijvoorbeeld `python -m http.server 8000`, en open `http://localhost:8000` in Edge.

## Achtergrondmuziek startscherm

De website speelt `muziek/kerst-achtergrond.mp3` zacht onder het startscherm, standaard aan. Ontbreekt dat bestand, dan verdwijnen de muziekknop en de vermelding vanzelf.

## Licenties

Zie [LICENTIES.txt](LICENTIES.txt).
