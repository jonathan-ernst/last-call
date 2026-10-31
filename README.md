# Last Call

Ein Fokus-Timer im Club-Look. Wähl ein Getränk und eine Dauer, dann wird deine Flasche abgefüllt, solange der Tab offen und sichtbar bleibt. Wechselst du länger als 10 Sekunden weg, zerbricht sie. Jede volle Flasche landet auf deiner LED-Tanzfläche.

## Benutzen

`index.html` im Browser öffnen. Es gibt keine Abhängigkeiten und keinen Build-Schritt.

Sessions werden im `localStorage` des Browsers gespeichert. Als Claude-Artifact geöffnet, speichert die Seite zusätzlich im Claude-Konto.

## Funktionen

- 8 Getränke: Bier, Rotwein, Champagner, Vodka, Gin, Tequila, Whisky, Rum
- Sessions von 5 bis 120 Minuten
- 10 Sekunden Kulanz beim Wegwechseln, danach zerbricht die Flasche
- Tanzfläche pro Tag, mit Statistik (Minuten, Flaschen, 7 Tage, Serie) und Sammlung
