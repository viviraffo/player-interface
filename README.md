# Player Movement Logic (OOP Architecture) 🎮

Dieses Projekt demonstriert fortgeschrittene objektorientierte Programmierung (OOP) in Python. Es nutzt abstrakte Basisklassen, um ein flexibles System für Spielfiguren und deren Bewegungsmuster auf einem Koordinatensystem zu erstellen.

## Highlights
- **Abstraktion:** Einsatz des `abc`-Moduls (Abstract Base Classes), um ein striktes Interface für Spielfiguren zu definieren.
- **Vererbung:** Die Klasse `Pawn` erbt von der Basisklasse `Player` und erweitert deren Funktionalität.
- **Zustandsverwaltung:** Das Programm speichert nicht nur die aktuelle Position, sondern protokolliert den gesamten Pfad der Figur.
- **Dynamische Logik:** Die `level_up`-Funktion erweitert zur Laufzeit die möglichen Bewegungsmuster der Figur.

## Software-Architektur

Das Projekt folgt dem Prinzip der Erweiterbarkeit. Neue Figuren (wie `Knight` oder `Queen`) können einfach hinzugefügt werden, indem sie die `Player`-Klasse implementieren.



## Voraussetzungen
Um dieses Projekt auszuführen, benötigst du:
- **Python 3.6** oder höher.

## Installation & Ausführung

1. **Repository klonen:**
   ```bash
   git clone [https://github.com/viviraffo/player-interface.git](https://github.com/viviraffo/player-interface.git)
