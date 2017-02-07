# Grazer Gemeinderatswahlen 2012 & 2017

Die Seite ist ein Versuch, die von der Stadt Graz verfügbaren offenen Daten auf Bezirksebene mit dem Wahlergebnis der Gemeinderatswahl 2017 zu verknüpfen. Für das Ergebnis-File wird testweise die API von [offenewahlen.at](http://offenewahlen.at) (siehe [https://offenewahlen-api.herokuapp.com/](https://offenewahlen-api.herokuapp.com/)) verwendet.

Da auf Bezirks- und Sprengelebene keine Wahlkarten sowie keine vorzeitig abgegebenen Stimmen ausgewiesen werden, entsprechen die Ergebnisse nur bedingt dem tatsächlichen Wahlverhalten in diesen Einheiten. Die Strukturdaten der Bezirke basieren ebenfalls nur teilweise auf den Wahlberechtigten, teilweise aber auch auf der gesamten Wohnbevölkerung. Entsprechend sollten die Darstellungen zurückhaltend interpretiert werden.

Der Code bezieht sich auf die Wahl 2012, er kann aber auch mit den Daten für 2017 verwendet werden - siehe Folder data2017 für die entsprechenden Grundlagen. Achtung: Das Ergebnis-json 2017 enthält die Zahl der Wahlberechtigten, der Wert kann entsprechend berechnet werden (siehe die comments im code).

Version 2012: http://vis.strategieanalysen.at/graz_bezirke2012/
Version 2017: http://vis.strategieanalysen.at/graz_bezirke/

Die Darstellungen basieren auf d3js, alle Daten stammen von [https://data.gv.at](https://data.gv.at).
