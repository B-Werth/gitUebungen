Aufgabe 2: Repository erzeugen und Änderungen
commiten
Stelle die Entwicklungsgeschichte des Projekts nach.
Lege ein neues leeres Verzeichnis an ( /gitUebungen ).
Initialisiere das git Repository inerhalb des Verzeichnisses.
$ git init
Folgende “Features” sind zu erarbeiten:
1. Erzeuge drei Dateien. ( README.md , helloWorld.c , config.json )
2. Ändere die Dateien mit folgenden Inhalt:

Erzeuge einzelne Commits, die jeweils genau ein neues “Feature” beinhalten.
Benutze git add und git reset (evtl. mit der Option -p ), um den Inhalt des Index genau zu
kontrollieren.
Benutze git commit um die Änderungen ins Repository zu schreiben
Benutze git diff und git diff --cached , um zu prüfen, dass der Index genau die gewünschten
Änderungen enthält.
Am Ende soll es möglich sein, nachzuvollziehen, welche Features durch welche Änderungen im Code
bewirkt wurden.