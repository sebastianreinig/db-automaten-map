# DB Automaten auf einer Karte
Die Anwendung zeigt die DB-Automaten auf einer Karte an.

Die Datenquelle enthält nur Postleitzahlen, daher wurde ein Mapping gemacht.
Danke an: https://github.com/WZBSocialScienceCenter/plz_geocoord/


# Datenquelle
**https://www.bahn.de/service/buchung/wege_zur_fahrkarte/automat**
Die Daten kommen aus folgendem JSON, welches öffentlich zugänglich ist.
![Bildschirmfoto 2022-08-31 um 20 53 46](https://user-images.githubusercontent.com/18229650/187759814-c8a8969a-afb7-4b71-9e54-1efee8e2d919.png)

Hier sind die Daten als xlsx zu finden:
https://github.com/sebastianreinig/db-automaten-map/blob/22583e858c75fef8e9309a46c64bb96122d2e356/dbautomaten.xlsx

# Demo
![Bildschirmfoto 2022-09-01 um 22 30 44](https://user-images.githubusercontent.com/18229650/188006488-3b28ac76-f3a2-458a-8294-1efb4ad4f41d.png)
https://sebastianreinig.github.io/db-automaten-map/

# Bekannte Fehler
1) Es gibt in den Daten noch ein Fehler mit führenden Nullen, daher fehlen in der Gegend von Dresden und Leipzig die Automaten.
2) Umgang mit mehreren Automaten pro Marker:
3)  ![Bildschirmfoto 2022-09-03 um 11 01 43](https://user-images.githubusercontent.com/18229650/188263772-e8ab8de2-c7ee-444e-8c2c-89c2d6d30573.png


# Danke/Credits

Folgende Karte wurde als Basis genommen:
https://handsondataviz.github.io/leaflet-map-csv/
https://github.com/stefanocudini/leaflet-search
