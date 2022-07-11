
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
|     0.54        |     Jan. 1996             | Neue Speicherverwaltung, mit der das Laden großer Bilddateien kein Problem mehr ist. |
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

Skripte und Plug-ins für GIMP können interaktiv ausgeführt werden, das heisst ohne Interaktion eines Benutzers. Wiederkehrende (auch komplexe) Bildbearbeitungsvorgänge können so automatisiert werden. 

Grafiken für eine Webseite können beispielsweise direkt über Skripte erzeugt werden, man kann bei einer grossen Anzahl an Bilddateien eine Farbkorrektur vornehmen oder das Grafikformat ändern. Hinweise zu Verwendung solcher Skripte finden sich GIMP-Wikibook.

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

# 39 Tools in GIMP anwendbar

## Bewegen
Mit dem Verschieben-Werkzeug kann man einzelne Ebenen und Objekte auf deiner Leinwand verschieben. Man kann sie wählen, ob Sie sich nach Ebenen, Auswahlen oder Pfaden bewegen möchten. Es ist ein ziemlich verbreitetes Werkzeug, das man beim Erstellen von Designs häufig verwenden, aber vielleicht nicht so oft, wenn man nur Fotos nachbessern.

## Ausrichtung

Mit dem Ausrichtungswerkzeug kann man verschiedene Ebenen in deinem Arbeitsbereich anordnen und neu positionieren. Man kann sie gemäß ihren Kanten oder Mittelpunkten auf beiden Achsen ausrichten, und du kannst dies alles relativ zum Bild, zur aktiven Ebene, zur Auswahl oder zu beliebigen anderen Zahlenvorgaben tun.

## Rechteck auswählen
Das Rechteck-Auswahlwerkzeug wird verwendet, um Auswahlen auf deiner Leinwand in Form eines vierseitigen Objekts oder eines Rechtecks zu erstellen. Das Tool verfügt über viele nützliche Einstellungen, wie die Möglichkeit, rechteckige Auswahlen mit abgerundeten Ecken, gefiederten Kanten und sogar mit Führungslinien für mehr Präzision zu erstellen. Die Auswahl kann dann für eine Vielzahl unterschiedlicher Aufgaben verwendet werden, z. B. zum Füllen mit Farbe, zum Löschen von Bereichen und zum Zuschneiden von Bildabschnitten.

## Ellipse
Das Ellipsen-Auswahlwerkzeug funktioniert ähnlich wie das Rechteck-Auswahlwerkzeug, nur dass man damit abgerundete Auswahlen oder eine Ellipse erstellen können. Es hat auch die gleichen nützlichen Funktionen eingebaut, wie z. B. die Möglichkeit, die Ränder deiner Auswahl auszuweichen und ein festes Seitenverhältnis zu wählen, wenn man möchte.

## Frei
Mit dem Free Select Tool kann man basierend auf deiner eigenen Handbewegung eine Auswahl auf deinem Bild treffen. Du kannst klicken, um einzelne Punkte zu erstellen, die durch gerade Linien verbunden sind, oder einfach klicken und ziehen, um deine eigene Auswahl zu zeichnen.

Das Werkzeug funktioniert hervorragend, wenn es in einem sehr beiläufigen Kontext verwendet wird, z. B. beim Ausfüllen eines geneigten Felds oder beim Zeichnen einer groben Auswahl um ein klar definiertes Motiv. Der Nachteil ist jedoch, dass ihm die Präzision fehlt, die du von einigen der anderen Werkzeuge erhalten.

## Schere
Das Scissors Select Tool funktioniert ähnlich wie das Free Select Tool, nur dass es etwas intuitiver ist. Während du klickst, um deine Punkte zu erstellen, versucht es zu erraten, wo sich die Ränder deines Motivs befinden. Wenn du mit dem Erstellen deiner Auswahl fertig sind, kannst du zurückgehen und die Position deiner Punkte für mehr Präzision manuell anpassen.

Wie du dir vorstellen kannst, ist das Tool nicht immer perfekt, wenn es darum geht, die Grenzen deines Motivs einzuschätzen, aber es ist großartig, wenn du nur sehr schnell eine rudimentäre Auswahl benötigst.

## Vordergrund
Das Vordergrundauswahl-Werkzeug ist eine wirklich fortschrittliche und intuitive Möglichkeit, eine Auswahl um ein Motiv in deinem Foto zu erstellen, das nicht leicht durch harte Kanten und kontrastierende Farben definiert werden kann. Ein gutes Beispiel hierfür wäre das Zuschneiden von Haarsträhnen. Das Tool ermöglicht es dir, einen sehr rudimentären Umriss um Ihr Motiv zu malen, und dann wird es seine Magie entfalten, indem es schätzt, wo die Auswahl generiert werden soll.

Der verwendete Algorithmus ist nicht immer perfekt, aber du kannst eine nahezu perfekte Auswahl erhalten, indem du die Werkzeugeinstellungen entsprechend deinem Bild anpassen und in den Bereichen, die du ausfüllen, etwas präziser vorgehen.

## Unscharf
Mit dem Fuzzy-Auswahl-Tool kannst du eine Auswahl auf lokalisierten Bereichen deiner Leinwand erstellen, basierend darauf, wie ähnlich die nahe gelegenen Pixel sein können. Wenn du auf deine Leinwand klickst, wird die zu erstellende Auswahl angezeigt. Du kannst den Schwellenwert erhöhen, indem du ihn nach unten ziehst, oder ihn verringern, indem du ihn nach oben ziehst.

Die Funktion „Maske zeichnen“ in den Werkzeugeinstellungen ermöglicht das Anzeigen einer farbigen Maske innerhalb deiner Auswahl, damit du eine bessere Vorstellung davon bekommen, was erstellt wird.

Ich habe festgestellt, dass das Tool sehr nützlich ist, um Motive aus Fotos zuzuschneiden, wenn sie sich auf einem Hintergrund mit Farbverlauf befinden, wie zum Beispiel einem Sonnenuntergang.

## Wählen Sie nach Farbe
Das Werkzeug „Nach Farbe auswählen“ ähnelt dem Werkzeug „Fuzzy-Auswahl“, nur dass du damit eine Auswahl basierend auf einer bestimmten Farbe erstellen können. Du kannst den Schwellenwert auch erhöhen, um verschiedene Anteile dieser Farbe einzubeziehen.

Das Tool kann sehr nützlich sein, wenn Sie die Farben bestimmter Bereiche deiner Fotos ändern und den Rest unverändert lassen möchten.

## Zuschneiden
Mit dem Zuschneidewerkzeug kannst du die Grenzen deines Bildes ändern. Es ändert oder transformiert jedoch nicht unbedingt das Bild selbst, sondern ermöglicht dir nur, die Ränder deines Dokuments neu zu definieren. Das Werkzeug kann verwendet werden, um das gesamte Bild oder nur eine einzelne Ebene deiner Wahl zuzuschneiden.

Das Tool verfügt über verschiedene integrierte Einstellungen, mit denen du dein Bild basierend auf einer bestimmten Größe oder einem bestimmten Seitenverhältnis zuschneiden kannst, wenn du dies benötigst.

## Drehen
Mit dem Drehwerkzeug kannst du Bilder und Objekte auf einer einzelnen Ebene um eine Achse drehen, die du beliebig platzieren können. Klicke und ziehe einfach auf deiner Ebene, um sie zu drehen. Wenn Sie die Umschalttaste gedrückt halten, wird es in 15-Grad-Schritten arretiert, falls du eine präzisere Drehung benötigen. Du kannst  die Position des Rotationspunkts auch ändern, indem du das abgerundete Fadenkreuz beliebig verschieben. Wenn du das Fadenkreuz irgendwann wieder in der Mitte platzieren möchten, klicke einfach auf die Schaltfläche „Zurücksetzen“ in den Werkzeugeinstellungen.

## Skala
Mit dem Skalierungswerkzeug können Sie die Größe deiner Bilder Schicht für Schicht ändern. Klicken Sie einfach auf Ihr Bild und ziehen Sie es, um es zu verkleinern oder zu vergrößern. Mit den Werkzeugeinstellungen kannst du das Seitenverhältnis sperren, falls Sie Ihr Bild skalieren möchten, ohne die Abmessungen zu verzerren.

Das Tool funktioniert nicht nur auf Ebenen. Es funktioniert auch mit Auswahlen, Pfaden und dem gesamten Bild selbst.

### Scheren
Mit dem Scherwerkzeug kannst du deine Bilder verzerren, indem Sie sie entweder vertikal oder horizontal scheren. Um vertikal zu scheren, klicken und ziehen Sie in einer Auf- und Abbewegung. Um horizontal zu scheren, klicken und ziehen Sie in einer Links- und Rechtsbewegung. Sie können auch mit den Eingabewerten im Werkzeugeinstellungsfeld um einen bestimmten Grad scheren

## Flip
Das Flip-Tool ist ein einfaches Werkzeug, mit dem Sie deine Bilder entweder auf der vertikalen oder horizontalen Achse spiegeln können. Um deine Bilder zu spiegeln, klicken Sie einfach darauf. Ob es vertikal oder horizontal gespiegelt wird, wird durch die Einstellung bestimmt, die Sie im Werkzeugeinstellungsmenü auswählen.

Dies unterscheidet sich vom Drehen deiner Bilder darin, dass sie gespiegelt werden, anstatt deine Ausrichtung zu ändern.

## Perspektive
Mit dem Perspektivenwerkzeug kannst du die Perspektive einer bestimmten Ebene ändern, indem Sie einen der 4 Knoten in jeder Ecke neu positionieren. Sie können jede Ecke einzeln oder als ganze Einheit ändern, indem Sie die Option „Um die Mitte herum“ in den Werkzeugeinstellungen aktivieren. Sie müssen die Knoten in den Ecken jedoch nicht verwenden. Sie können irgendwo auf die Ebene klicken und die Perspektive des Bildes relativ zu deinem Auswahlpunkt ändern.

## Einheitliche Transformation
Das Unified Transform Tool bietet jede Menge Nützlichkeit und Vielseitigkeit, da es im Wesentlichen eine Vielzahl von Tools in einem kombiniert. Sie können es verwenden, um Bilder auf einer bestimmten Ebene zu verschieben, zu skalieren, zu scheren, zu drehen und die Perspektive zu ändern.

Sie können alle diese Anpassungen auf einmal auf einer einzigen Vorschauebene vornehmen und sie dann abschließen, wenn Sie fertig sind. Sie können es auch auf die vorherigen Einstellungen zurücksetzen, wenn Sie etwas benötigen

## 3D-Transformation
Das 3D-Transformationswerkzeug erzeugt einen ähnlichen Effekt wie das Perspektivenwerkzeug, nur dass es auf ein Seitenverhältnis fixiert ist, das hilft, ein realistisches 3D-Aussehen beizubehalten. Wenn Sie das Werkzeug verwenden, kannst du die Einstellung der Z-Achse jederzeit aktivieren, um die Drehung der Ebene zu ändern, während Sie daran arbeiten.

## Transformieren behandeln	
Mit dem Griff-Transformationswerkzeug kannst du Ihr Bild mit etwas mehr freier Handsteuerung als mit den anderen Werkzeugen umwandeln. Klicken Sie einfach auf Ihr Bild, um einen Punkt hinzuzufügen. Jetzt kannst du Ihr Bild um diesen Punkt skalieren und drehen. Wenn Sie einen zweiten Punkt hinzufügen, kannst du Ihr Bild basierend auf den Positionen dieser beiden Punkte scheren, und das Hinzufügen eines dritten und vierten Punkts ermöglicht es Ihnen, die Perspektive deines Bilds basierend auf der Position dieser Punkte zu ändern.

Sie können deine Zugriffspunkte jederzeit neu positionieren, indem Sie die Umschalttaste gedrückt halten und sie anklicken und ziehen, oder Sie kannst du löschen, indem Sie die Strg-Taste gedrückt halten und darauf klicken.
 


## Warp-Transformation
Das Warp Transform Tool funktioniert ähnlich wie ein Pinsel, nur dass Sie die Pixel deines Bildes verschieben, anstatt etwas hinzuzufügen. Wie Sie sehen können, kannst du Ihr Bild verzerren, indem Sie diese Pixel verschieben.

Es gibt verschiedene Methoden, um Ihr Bild zu verzerren. Die Bewegungsfunktion ist die Standardeinstellung, aber es gibt auch Einstellungen, mit denen Sie sich verziehen können, indem Sie wachsen, schrumpfen und wirbeln.

## Käfig-Transformation
Mit dem Käfig-Transformationswerkzeug können Sie ein Bild basierend auf einzelnen Punkten, die Sie manuell um dieses Bild herum platzieren, verziehen und verzerren. Durch Klicken und Ziehen dieser Punkte wird das Bild so verzerrt, dass es beim Ändern in den Begrenzungsrahmen passt.

## Eimer füllen
Das Füllwerkzeug wird verwendet, um bestimmte Bereiche deines Bildes mit einer Füllung oder einem Muster deiner Wahl zu füllen. Sie können wählen, ob Sie ganze Ebenen, Auswahlen oder nur Bereiche füllen möchten, die dieselbe Farbe enthalten, auf die Sie geklickt haben. Sie können den Schwellenwert auch so anpassen, dass er benachbarte Farben enthält, die möglicherweise einen ähnlichen, aber leicht unterschiedlichen Farbton verwenden.

## Gradient
Mit dem Verlaufswerkzeug können Sie eine Auswahl mit einem Verlauf oder einem Übergang zwischen zwei verschiedenen Farben deiner Wahl füllen. Du kannst deinen Farbverlauf auf Ihren ausgewählten Vorder- und Hintergrundfarben basieren oder aus einer Vielzahl von Voreinstellungen wählen. Mit dem Werkzeug kannst du lineare Farbverläufe erstellen, die einem geraden Pfad folgen, radiale Farbverläufe, die einem abgerundeten Pfad folgen, und mehr

## Pinsel
Der Pinsel wird verwendet, um sanfte Striche in einer Farbe oder einem Muster deiner Wahl auf deine Bilder zu malen. Es gibt eine Vielzahl von Pinseln in verschiedenen Formen zur Auswahl, zusammen mit einer Fülle von Einstellungen, die bestimmen, wie sich der Pinsel verhält, wenn Sie damit malen. Sie können auch die Härte, Deckkraft, den Abstand und sogar die Kraft sowie verschiedene andere Einstellungen anpassen.

## Bleistift
Das Bleistift-Werkzeug funktioniert ähnlich wie der Pinsel. Es ermöglicht Ihnen, mit einer Vielzahl von Formen und Verhaltensweisen manuell auf Ihr Bild zu zeichnen. Es hat auch viele der gleichen Einstellungen. Der einzige Unterschied besteht darin, dass kein Anti-Aliasing verwendet wird, was bedeutet, dass Sie solide, harte Kanten ohne Weichheit oder Auslaufen erhalten, unabhängig von Ihrem gewählten Pinsel oder Ihren Einstellungen.

## Airbrush
Das Airbrush-Werkzeug funktioniert ebenfalls ähnlich wie der Pinsel, aber der Hauptunterschied besteht in der Art und Weise, wie es die Farbe auf Ihr Bild aufträgt. Die Airbrush funktioniert eher wie eine echte Airbrush: Je länger Sie sie über einen bestimmten Bereich halten, desto dunkler wird die Farbe.

Das Airbrush-Werkzeug ist auch mit den meisten Einstellungen und Funktionen ausgestattet, mit denen die Pinsel- und Stiftwerkzeuge geliefert werden.

## Tintenwerkzeug
Die Idee hinter dem Tintenwerkzeug ist, dass es das Verhalten eines echten Dip-Stifts oder Kalligraphiestifts simulieren soll, indem es basierend auf der Geschwindigkeit und Richtung Ihrer Handbewegung zeichnet. Schnellere Bewegungen führen zu dünneren Strichen, während langsamere Bewegungen zu dickeren Strichen führen.

Das Tintenwerkzeug hat viele der gleichen Einstellungen wie Pinsel, Bleistift und Airbrush.

## Mein Pinsel
MyPaint ist eine Open-Source-Anwendung mit Schwerpunkt auf Malerei im Gegensatz zur Bildbearbeitung und wird über dieses Tool in GIMP integriert.

MyPaint-Pinsel sind in ihren Texturen und Verhaltensweisen etwas fortgeschrittener als die Standardpinsel in GIMP. Sie können verwendet werden, um realistisch aussehende Bleistiftskizzen, Flecken, Acryl und mehr zu erstellen.

## Radiergummi
Der Radiergummi wird verwendet, um Pixel aus Ihren Bildern zu löschen. Es funktioniert wie ein Pinsel, bei dem Sie verschiedene Formen, Größen und Verhaltensweisen auswählen können. Der einzige Unterschied besteht darin, dass Pixel aus Ihren Bildern entfernt werden, anstatt sie hinzuzufügen.

Wenn Sie der Ebene, an der Sie gerade arbeiten, einen Alphakanal hinzugefügt haben, löscht der Radiergummi die Transparenz oder die darunter liegende Ebene. Wenn Sie keinen Alphakanal hinzugefügt haben, wird er zu Weiß gelöscht.

Sie können den Radiergummi jederzeit umkehren, indem Sie die Alt-Taste auf Ihrer Tastatur gedrückt halten. Auf diese Weise können Sie die gelöschten Bereiche wieder mit dem füllen, was zuvor dort war.

## Klon
Mit dem Klonwerkzeug können Sie einen bestimmten Bereich Ihres Bildes als eine Art Pinsel zum Malen in anderen Bereichen Ihres Bildes verwenden. Sie können jede Ihrer Pinselvoreinstellungen zum Erstellen Ihrer Musterauswahl verwenden. Wenn Sie dann Pinselstriche erstellen, bewegt sich die Musterauswahl entsprechend Ihrer Handbewegung.

## Perspektivenklon
Das Perspective Clone Tool funktioniert ähnlich wie das Clone Tool. Es hat die meisten der gleichen Funktionen und Einstellungen, aber der Hauptunterschied besteht darin, dass Sie Ihre Objekte basierend auf einer Simulation der Perspektive in Ihrem Bild klonen können, die Sie definieren können. Dies kann sehr nützlich sein, um Objekte in Ihren Fotos zu bewegen und gleichzeitig ein realistisches Aussehen zu erhalten.

## Heilung
Mit dem Reparaturwerkzeug können Sie kleinere Unvollkommenheiten in Fotos korrigieren. Sein Verhalten ist dem des Klonen-Werkzeugs sehr ähnlich, nur dass der Effekt viel weniger ausgeprägt ist und es Ihre Musterauswahl besser nahtlos in die gestempelten Bereiche einfügt. Halten Sie einfach die Strg-Taste gedrückt und klicken Sie auf einen Bereich, um Ihre Auswahl zu erstellen, und malen Sie dann über die Bereiche, auf die Sie sie anwenden möchten.

## Verschmieren
Das Wischwerkzeug kann verwendet werden, um die Pixel in einem Bild relativ zu den Eigenschaften der Pinselform und den verwendeten Einstellungen zu verschieben. Wie Sie in der Demonstration sehen können, werden keine Pixel hinzugefügt oder entfernt. Es bewegt sie nur herum, um einen Wischeffekt zu erzeugen, der beim Malen nützlich sein könnte.

## Unschärfe schärfen
Das Werkzeug Weichzeichnen und Schärfen funktioniert ähnlich wie die Filtereffekte, mit denen Sie Ihre Bilder weichzeichnen und schärfen können, nur dass Sie es mit Pinseleinstellungen Ihrer Wahl auf lokalisierte Bereiche anwenden können. Sie können in den Werkzeugeinstellungen wählen, ob Sie weichzeichnen oder schärfen möchten, und dann die Intensität des Effekts mit dem Schieberegler Rate steuern.

## Ausweichen & Brennen
Das Dodge & Burn Tool wird zum Aufhellen und Abdunkeln bestimmter Bereiche Ihres Bildes verwendet, basierend auf dem von Ihnen gewählten Pinsel und seinen Einstellungen.

Dodge kann verwendet werden, um Schatten aufzuhellen, während burn und verwendet werden, um Schatten abzudunkeln. Sie können die Intensität des Effekts anpassen, indem Sie die Belichtung in den Werkzeugeinstellungen ändern, und Sie können den Effekt auch nur auf die Schatten, Mitteltöne oder Lichter anwenden.

## Pfade
Das Pfade-Werkzeug wird zum manuellen Zeichnen einer Reihe von Punkten verwendet, die durch eine Linie oder einen „Pfad“ miteinander verbunden sind. Die Linien können gerade oder gekrümmt sein, und die Ankerpunkte des Pfads können individuell angepasst werden, um genau die gewünschte Form zu erhalten.

Das Pfade-Werkzeug ist ideal zum Erstellen von Auswahlen, da Sie damit die flüssigsten und präzisesten Zeichnungen erstellen können.

## Text
Das Textwerkzeug wird zum Generieren von Text und Formulierungen auf Ihrer Leinwand verwendet. Ihr Text kann in allen Schriftarten verwendet werden, die Sie auf Ihrem Betriebssystem installiert haben, und kann mit den anderen Tools bearbeitet werden, als wäre es jedes andere Bild. Sie können Ihren Text auch entlang von Pfaden fließen lassen, wenn Sie möchten.

## Farbwähler
Mit dem Farbwähler-Tool können Sie eine Farbe an einer beliebigen Stelle in Ihrem Bild aufnehmen, um sie als Vordergrundfarbe zu verwenden. Wenn Sie auf die Farbe klicken, wird sie als Vordergrundfarbe festgelegt, während Sie bei gedrückter Strg-Taste darauf klicken, um sie als Hintergrundfarbe festzulegen. Durch Klicken und Ziehen können Sie das gesamte Bild durchsuchen, um die gewünschte Farbe zu finden.

## Messen
Das Messwerkzeug wird verwendet, um einfache Messungen an Ihrem Bild vorzunehmen. Sie können klicken und ziehen, um eine Linie zu erstellen, dann zeigt die Statusleiste unten auf der Seite die Länge dieser Linie in Pixel, Zoll, Zentimeter oder einem anderen gewünschten Inkrement an.

Die Statusleiste zeigt auch den Grad Ihrer Linie relativ zur horizontalen oder vertikalen Achse an. Sie können im Werkzeugeinstellungsmenü ändern, auf welches es verweist.

## Zoomen
Schließlich wird das Zoom-Werkzeug zum Vergrößern und Verkleinern Ihres Bildes verwendet. Sie können hineinzoomen, um feine Details zu sehen, oder herauszoomen, um zu sehen, wie Ihr Design in einem verkleinerten Kontext aussehen würde. Sie können jederzeit 1 auf der Tastatur drücken, um wieder auf 100 % zu verkleinern.

# 14 Angewendete Tools in Photoshop

## Magnetisches Lasso Tool

Heftet sich an den Rand eines ungenau ausgewählten Objektes.

## Schnellauswahl Tool

Dieses Tool lässt dich das Objekt einfach auswählen während der Benutzung des Pinsel-Tools. Für eine präzisere Auswahl kann man in der Optionen-Leiste "Auto Enhance" einschalten.

## Zauberstab Tool

Wähle mit dem Zauberstab einfach alle ähnlichen Farben mit einem Klick aus!

## Pipetten-Tool

Lässt dich eine bestimmte Farbe im Bild herauspicken, um mit dieser danach weiterzuarbeiten.

## Freistellungs-Tool

Schneide ganz einfach dein Bild zurecht und entferne somit ungewollte Teile des Bildes.

## Bereichsreparatur-Tool

Das Bereichsreparatur-Tool wird normalerweise für kleine Bereiche verwendet, welche kleine Fehler und Unschönheiten vorweisen.

## Healing Brush-Tool

Das Healing Brush-Tool wird für grosse Beriche verwendet, auf welchen beispielsweise unerwünschte Personen zu sehen sind und entfernt werden wollen.

## Radiergummi Tool

Mit dem Radiergummi kannst du Pixel dauerhaft löschen.

## Unschärfe Tool

Benutze das Unschärfe Tool um ein Objekt/eine Fläche im Bild unscharf zu machen.

## Schärfen Tool

Schärft ein Objekt oder eine Fläche im Bild

## Burn Tool

Das Burn Tool lässt dich Flächen schwärzen und Schatten von Objekten generieren.

## Dodge Tool

Mit dem Dodge Tool kannst du einzelne Flächen aufhellen. Es ist sehr gut einsetzbar auch für Licht-Effekte in Bildern.

## Zoom Tool

Damit kannst du die Ansicht im Bild vergrössern und verkleinern. Zum Vergrössern musst du ganz einfach klicken, für das Verkleinern drückst du zusätzlich noch die ALT-Taste.

## Hand Tool

Mit diesem Werkzeug kannst du ein Bild, ein Layer oder eine ausgewählte Fläche anklicken und auf dem Bildschirm umherziehen.
