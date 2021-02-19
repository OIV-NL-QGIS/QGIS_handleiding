# OIV project

## Snelstart handleiding voor eindgebruikers OIV-Plugin

Klik op onderstaande link om naar de gebruikershandleiding te gaan.
Hierin vind je de instructies om het programma te installeren en te gebruiken.

[Documentatie (in ontwikkeling)]

## Over het project

OIV (operationele informatievoorziening) is een onderdeel van het OIV NL QGIS-applicatielandschap. Binnen de geo-informatieketen vormt OIV een bron voor onder andere KaartViewers geoportaal en de voertuigviewers

OIV zelf is opgebouwd uit een aantal onderdelen: een QGIS project met kaartlagen en tekenmogelijkheden, PostGIS database definities en Geoserver kaartlagen met bijbehorende opmaak en definities.

Vanuit QGIS kan middels een WFS-T (GeoJSON) verbinding gecommuniceerd worden met de database. De database gegevens worden vervolgens door de Geoserver weer vertaald in een kaartlaag die via services (WFS/WMS) bevraagbaar is in afnemende applicaties. Middels de ETL-koppeling is het ook mogelijk om gegevens en metadata te bevragen in dashboards.
