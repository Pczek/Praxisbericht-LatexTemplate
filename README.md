#Praxisbericht-LatexTemplate
Dieses Repository enthält eine LaTeX Vorlage für Praxisberichte zur Abgabe an der Duale Hochschule Baden-Württemberg. Als Partner Unternehmen ist in dieser Vorlage das Deutsche Zentrum für Luft- und Raumfahrt aufgeführt. Die Vorlage ist in UTF-8 kodiert!

##Aufbau
Der Kern der Vorlage ist die `main.tex`, in dieser Datei werden alle weiteren benötigten TeX Dateien eingebunden. Die TeX Dateien sind in folgender Ordnersturktur abgelegt.

* `./header/`- header Dateien
* `./essentials/`- Deckblatt, Einstellungen, Pakete
* `./part1/`- Hauptteil der Arbeit
* `./images/`- verwendete Grafiken
* `./appendix/`- Anhang
* `./bib/`- Literatur

##Wichtige Dateien
* `./header/packages.tex` — bindet die benötigten Packete ein
* `./header/macros.tex` — setzt wichtige Variablen wie `\autor`, `\matrikelnr` etc. sowie erstellt macros zum einfacheren Einbinden von Bildern und Tabellen
* `./header/preferences.tex` - setzt die Einstellungen für das Layout der Vorlage

* `./essentials/frontpage.tex` — Deckblatt nach der Vorgabe der DHBW
* `./essentials/declaration.tex` — Eidestattliche Erklärung zur eigenständigen anfertigung der Arbeit
* `./essentials/acronym.tex` — Abkürzungverzeichniss
