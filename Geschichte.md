# 1 Geschichte

### Entstehung und Verbreitung

Die erste öffentliche Testversion von GIMP wurde von Peter Mattis am 21. November 1995 in der Newsgroup angekündigt. Zusammen mit Spencer Kimball hatte er das Programm als Studienarbeit entwickelt. 

Die erste offizielle Verison erschien im Januar 1996.
Die Version 1.0 wurde am 5. Juni 1998 veröffentlicht.

Zu diesem Zeitpunkt war GIMP ein umfangreiches Programm, das unter anderem mit einem Plug-in-System, beliebigem Rückgängigmachen und Wiederholen, intelligenter Schere, Unterstützung von 8, 15, 16 und 24 Bit Farbtiefe pro Bild, Zoom und Verschieben in Echtzeit, Bearbeitungen mehrerer Bilder, Unterstützung der Formate GIF, JPEG, PNG, TIFF und XPM sowie vielen Auswahl und Bearbeitungswerkzeugen aufwarten konnte.

Durch Linux erlangte GIMP eine grosse Verbreitung und estabilisierte sich dort im Laufe der Zeit als Marktführer für digitale Bildbearbeitung. Das Programm ist Bestandteil vieler Linus-Distributionen, die nicht konsequent auf GTK () basierende Programme verzichten.

Nach veröffentlichung von Ubuntu 9.10 beschlossen, in Ubuntu 10.04 GIMP nicht mehr vorzuinstallieren, da es "zu kompliziert" sei, es zu viel Platz auf der Installation-CD benötige und bereits F-Sport mitgeliefert werde. Ausserdem könne man es weiterhin über die Software-Repository nachladen.

### Versionen

|     Version     |     Erscheinungsdatum     |     Anmerkung     |
| --------------- | ------------------------- | ----------------- |
|     n.n         |     21. Nov. 1995         | Erste veröffentlichte Testversion|
|     0.54        |     Jan. 1996             | Neue Speicherverwaltung, mit der das Laden        großer Bilddateien kein Problem mehr ist. |
|     1.0         |     05. Juni 1998         | Neue Speicherverwaltung, mit der das Laden großer Bilddateien kein Problem mehr ist. |
|     1.2         |     25. Dez. 2000         | Fehlerbereinigungen, Überarbeitung der grafischen Oberfläche. |
|     2.0         |     24. März 2004         | Erstmals einfaches CMYK, SVG-Import und -Export, rudimentäre Druckvorstufe, bessere Pfad- und Text-Werkzeuge, weitere Änderungen an der grafischen Oberfläche.  |
|     2.2         |     19. Dez. 2004         | Vorschaufunktion für zahlreiche Werkzeuge, Anpassung der grafischen Oberfläche.  |
|     2.4         |     24. Okt. 2007         | Grafische Oberfläche überarbeitet, verbesserte Werkzeuge zur Freistellung, Skalierung und Text an Pfaden; einzelnes, unabhängiges Rückgängig-Machen länger zurückliegender Bearbeitungsschritte.  |
|     2.6         |     01. Okt. 2008         | 	Umstieg auf neue Grafikbibliothek Generic Graphics Library (GEGL) begonnen. |
|     2.8         |     03. Mai 2012          | ptionaler Ein-Fenster-Modus, Ebenengruppen, Texteingabe direkt auf der Leinwand, Speichern und Exportieren überarbeitet, Layercomposing mit GEGL. |
|     2.8.22      |     11. Mai 2017          | Bugfix, zusätzliche Hilfedatei in deutsch 2.8.2 |
|     2.9         |     27. Nov. 2015         | Direkt-Vorschau-Filter, experimentelle Integration von Hardware-Beschleunigung. |
|     2.9.8       |     12. Dez. 2017         | Neue Features und Bugfix |
|     2.10.0      |     27. Apr. 2018         | Neue Funktionen der Version 2.9 weiter ausgebaut, verbesserte und vereinfachte Bildtransformationen, stark ausgebaute Skalierungsmethoden, GEGL komplett, Geschwindigkeitsverbesserungen durch Multicore-Nutzung und Hardware-Beschleunigung. |
|     2.10.30     |     21. Dez. 2021         | Diverse Fehler wurden behoben, verbesserte PSD Unterstützung und Plugin Anpassungen. |
|     2.99.10     |     25. Feb. 2022         | neues Plugin-API, verbesserte Unterstützung von Grafik-Tablets, vereinfachtes Theming, Multi-Layer-Support. |

### Umstellung auf GEGL

Mit der Version 2.6 das am 1. Oktober 2008 erschien wurde der Umstieg vom bisherigen Grafik-Kernel auf die neue unabhängige Bibliothek GEGL (Generic Graphics Library begonnen. Zum Freigabetermin waren noch nicht alle Funktionen portiert, sodass die erhoffte Unterstützung höherer Farbtiefen fehlte. Diese folgte in Version 2. 10, welche vollständig auf GEGL aufbat. GEGL arbeitet und unterstütz weitere Dateiformate von Digitalkamera. 

Die aufwendige Migration auf GEGL – überwiegend durch nur eine Person umgesetzt – blockierte über viele Jahre die Entwicklung und war der Hauptgrund für die langen Entwicklungsdauern von Version 2.8 auf 2.10 (6 Jahre).


# 2 Funktionsumfang

### Überblick

Die Bearbeitungsfunktionen sind über Werkzeugleisten, Menüs und dauerhaft eingeblendete Paletten (in Gimp "Dialog" genannt) zu erreichen. Diese enthalten sogenannte Filter für grafische Effekte, zudem Pinsel sowie Umwandlungs-, Auswahl-, Ebenen und Maskierungsfunktionen. Zum Standardumfang gehören eine Reihe von Pinseln,zudem sind alle Kantenschärfe und Deckung einstellbar. 

Andere können als Plugin installiert oder selbst erstellt werden, auch Photoshop-Pinsel können genutzt werden. Der Standardumfang von GIMP kann mit Erweiterungen und weiteren Pinseln von Drittanbietern erweitert werden. 
Weiterhin hat Gimp eine druckempfindliche Sprühdose für Grafiktabletts. Gimp unterstützt mehr als dreissig Dateiformate.

### Farbunterstützung

GIMP hat Farbpaletten für RGB, HSV, CMYK, ein Farbrad sowie Funktionen, um Farben aus einem Bild zu entnehmen (Pipette). Auch wenn das Programm eine CMYK-Palette anbietet, arbeitet es immer in RGB mit einer Farbtiefe bis 32 Bit. 

#### RGB
RGB ist der Farbraum, der mittels der Farben Rot, Grün und Blau gebildet wird. 
Dieser wird bei Monitoren, Fernseher oder Smartphones benutzt. 
Die Farben Rot, Grün und Blau werden als Lichtfarben bezeichnet und sind nicht im Druck wiederzugeben, da das Mischen der Lichtfarben auf Druckstoffen nicht möglich ist.

#### HSV

Der HSV-Farbraum ist der Farbraum etlicher Farbmodelle.
Hier ist der Farbort einer Farbe definiert mit Hilfe der drei Koordinaten.

#### CMYK

DMYK-Farbraum ist für den Druck

Es setzt sich aus den drei Farben Cyan, Magenta und Gelb sowie der Key Coulour Schwarz zusammen, die auf weissen Untergrund gedruckt werden. Je mehr Farbe aufgetragen wird, desto dunkler wird das Ergebnis.

## Automatisierte Bildbearbeitung durch Skripe

Alle Vorgänge in GIMP können durch sogenannte GIMP-Skripte automatisiert werden. 
Diese Art von Programmen kann durch den eingebauten (Skript-Fu) sowie über eine externe Anbindung von Perl, Python oder Tcl verarbeitet werden.

Die unterstützung das von Ruby geschrieben GIMP-Skripten befindet soch noch in einem experimentellen Stadium.

Skripte und Plug-ins für GIMP können interaktiv ausgeführt werden, das heisst ohne Interaktion eines Benutzers. Wiederkehrende (auch komplexe) Bildbearbeitungsvorgänge können so automatisiert werden. Grafiken für eine Webseite können beispielsweise direkt über Skripte erzeugt werden, man kann bei einer grossen Anzahl an Bilddateien eine Farbkorrektur vornehmen oder das Grafikformat ändern. Hinweise zu Verwendung solcher Skripte finden sich GIMP-Wikibook.

## Gimp ML

GimpML ist ein Plugin für Filter mit Maschinellem Lernen für GIMP 2.10.

* Maschinelles Lernen ist ein Oberbegriff für die „künstliche“ Generierung von Wissen aus Erfahrung


# 3 Eingestellte Modifikationen

#### CinePaint

Unter dem Namen CinePaint (früher Film Gimp) ist ein professioneller Ableger des Programmes entstanden, der sich durch größere Farbtiefen und ein Farbmanagement auszeichnet

#### GIMPshop

GIMPshop war eine Modifikation des GIMP die in Erscheinungsbild und Bedienung Adobe Photoshop angeglichen war. Der ursprüngliche Entwickler Scott Moschella wollte damit langjährigen Nutzern des kommerziellen Photoshops den Umstieg erleichtern.

#### GimPhoto

In der Tradition von GIMPshop steht GimPhoto, das ebenfalls mit einer Photoshop-ähnlicheren Bedienung aufwartete und über die kleine Anwendung GimPad noch mehr an individuelle Bedürfniss im Erscheinungsbild angepasst werden konnte.

