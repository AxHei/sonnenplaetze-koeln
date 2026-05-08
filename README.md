# Sonnenplätze Köln — Prototyp

Web-App, die für Köln-Deutz auf einer Karte zeigt, wo zur eingestellten Uhrzeit
Sonne oder Schatten in der Außengastronomie ist.

**Aktueller Stand:** 3D-Modell aller Gebäude in Köln-Deutz mit echten Dachformen,
basierend auf den offenen LoD2-Daten von Geobasis NRW.

## Daten

- 4 LoD2-Kacheln Köln-Deutz (Geobasis NRW, Datenlizenz Deutschland Zero 2.0)
- 2.539 Gebäude mit Footprint und Dachform
- Mesh: 150.787 Dreiecke, exportiert als binäres glTF (~6 MB)

## Stack

- MapLibre GL JS (Karte)
- three.js + glTF-Loader (3D-Gebäude)
- CARTO Positron (Hintergrundkarte, kostenlos)

## Geplante Erweiterungen

- Sonnenstandsberechnung mit SunCalc
- Schatten-Layer für die LoD2-Gebäude
- Außengastronomie-Punkte (OpenStreetMap)
- Pro Lokal: "Sonne / Schatten gerade?" mit grün/grau-Einfärbung
- Datum-/Uhrzeit-Regler
- Mobile Bedienung

## Lizenz

Code: MIT. Daten: jeweils Lizenz der Quelle (siehe Quellen im Machbarkeitsbericht).
