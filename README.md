# Repo für Stochastik (Informatiker)
__Disclaimer:__  Alle Dateien wurden im SS21 erstellt, auf Basis der Stocha Folien und des Buches "Stochastik"- von Hans-Otto Georgii.     
Es gibt __keine__ Garantie auf Richtigkeit/Vollständigkeit!  

## Kompilieren
Da scheinbar viele nur mit Overfleaf arbeiten und k.A. haben wie man "raw" LateX kompiliert hier eine kleine Anleitung:

### Linux
1. Downloaded TeX Live (oder eine andere LaTeX Distribution eurer Wahl) über dem packagemanager eures Vertrauens.
    - ggf. ist texlive gesplitet in mehrere Pakete, dann installiert die wichtigsten (z.B. core, science, math, pictures etc.)

    - wenn später Pakete fehlen wird euch das schnell auffallen

    - ggf. latexmk downloaden (meistens schon in texlive vorhanden) + deren dependencies (perl stuff; biber)

2. latexmk -pdf im Ordner mit der *.tex und fertig

### Windows 
1. Entweder die Schritte oben mittels WSL machen (Ubuntu z.B. mit apt)

2. MikTeX downloaden/installieren und auch wieder via. latexmk


### Code - OSS / VS-Code
Mit "LateX Workshop" hat man eine sehr gute Integration und kann alles in VS Code schreiben. 

Features sind z.B. im Fenster live pdf, automatisches kompilieren beim Speichern, Struktur Tree, Snippets + TikZ Integration, BibTeX Sachen etc..

## Ordner Struktur 
### Kapitel 2-9
Für jedes Kapitel gibt es eine LaTeX Datei, die das Kapitel so gut wie möglich zusammenfasst. 

Dabei werden meistens __nur die Klausurrelevanten Themen__ wirklich besprochen, d.h. vor allen Dingen in Kapitel 6/7 fehlen viele Konzepte im Bereich der Stetigen Stochastik. 

### Klausuraufgaben2021
Dieser Ordner beinhaltet den Aufgabenpool vom Stocha Kurs SS21 + eine selbstgeschriebene Musterlösung. 

__Disclaimer:__ 
- Auch für die Musterlösung gibt es __keine__ Garantie auf Richtigkeit/Vollständigkeit! 
Alle Aufgaben wurden von mir bearbeitet und korrigiert (verglichen mit Tutorlösungen / der Overleaf Lösung). 

- Die Aufgaben in Kapitel8/9 sind auch alle bearbeitet worden, jedoch wegen ihrer Länge/Ausführlichkeit auf Papier. 

- Falls es Interesse an diesen Aufgaben gibt, kann ich den Scan gerne mal später hochladen. 

- Bedenkt bitte auch, dass die Aufgaben in "Stichpunkten" gelöst sind, d.h. in der Klausur müsste man diese deutlich genauer ausschreiben/mathematisch sauberer Arbeiten!


Da ich keine Lust hatte über 90 Aufgaben in LaTeX zuschreiben, sind die meisten Aufgaben per Stift in die PDF "Klausuraufgaben_Pool_Losungen" geschrieben worden. 

Als weitere Lösungsquelle kann ich nur das [Overleaf Projekt](https://www.overleaf.com/4881732585fqgnvfvhxsnc) empfehlen. 

Diese Lösung wurde unabhängig vom Overleaf Projekt erstellt, jedoch paar Tage vor der Klausur (18.09.21) mit der Stocha_Aufgabenpool_Discord.pdf verglichen. 

## Verbesserungen/Ergänzungen + Anmerkung zur Klausur
Falls Leute Lust haben gewisse Sachen zu verbessern können diese sich gerne bei mir melden/einen Pull Request etc. erstellen.   

Die Klausuren im SS20/21 bestanden EXAKT aus den Poolaufgaben. 
D.h. es wurden keine Werte geändert, obwohl dies ja im Aufgabenpool steht.     
Dennoch würde ich dem nicht ganz vertrauen und Aufgaben immer genau lesen! 

Viel Erfolg/Glück an die armen Leute die Stocha noch hören müssen :D

## Update 18.07.22
Hab Teile von Bereich 8/9 die auf Papier waren ergänzt.
Leider ist die Reihenfolge beim Scannen falsch, sodass manche Aufgaben aus Bereich 9 in Bereich 8 sind.
Alle anderen Verteilungen etc. habe ich nicht mehr, aber die sollten sehr leicht sein wenn man die anderen Aufgaben verstanden hat.

## Update 27.07.22
Manche Lösungen von den Markov Aufgaben haben einen Flüchtigkeitsfehler. 
Für den Ergodensatz ist statt der transponierten Matrix die normale Übergangsmatrix verwendet worden, sodass das Gaußen und die resultierende W-Funktion p (Grenzverteilung) falsch sind!
D.h. beim selbst lösen/lernen darauf achten, die transponierte Version zu verwenden, statt die normale.
Die Theorie und die Rechenwege sollten dennoch korrekt sein.

Habe die Aufgaben wo der Fehler vorkommt mit blau markiert, damit nicht jemand den gleichen Fehler macht.