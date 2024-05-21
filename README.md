Hallo, dies sind einige Sachen, die ich Geschrieben habe.
Meine Visualstudio Projekte haben einmal eine ausführbare Datei und den Projektordner an sich.
8damenproblem.zip und Schach.zip sind Webanwendungen.

Hier werde Ich nun die Dateien kurz beschreiben:

-Whitenoise
Whitenoise ist ein Programm welches auf einem Fenster zufällig befärbte Rechtecke mit 5*5 Pixel Größe platziert.
Es ist ein Vorgänger für einen geplanten zufälligen Bildgenerator inspiriert von KI basierter Bildgeneration.

-TESTPROJ
Ein Test, um zu sehen in wie fern ich fähig bin in Winforms ein Spiel zu Programmiern.
Der Code ist verbesserungsbedürftig und enthält noch keine Kommentierung.
Den Meisten Code habe ich in meiner Freizeit während der Schule geschrieben.
Das Spielfeld nimmt inspiration aus den Schauchbrettern aus meinen Webanwendungen.
Prinzip des Spiels ist es möglichst viele Level zu schaffen und seinen Score zu erhöhen, indem man die Alle Gegner auf dem Spielfeld vernichtet.
Normale Gegner bewegen sich zufällig in eine der vier Richtungen.
Jede fünf Level kommt ein Bossgegner, welcher den Spieler verfolgt, mehrere Leben hat und auch schießen kann.
Die Level werden immer schwieriger mit erhöter Geschwindigkeit, mehr Gegnern und Stärkeren Bossen.
Der Spieler, welcher oben links erscheint, hat eine Vielzahl von Steuerungmöglichkeiten:
Pfeiltasten: Lassen den Spieler in die entsprechende Richtung laufen.
Q: Schießt ein Projektil, welches bei dem Aufprall mit einem Gegner diesem Schaden zufügt. Die Projektile sind auf 3 begrenzt und werden mit der Zeit nachgeladen. Diese Projektile erhöhen den Score um 30 Wenn sie einen Gegner vernichten.
W: Ein Durchtrennendes Projektil, welches nicht mit dem Aufprall gelöscht wird. Von diesen Projektilen kann nur eins gleichzeitig auf dem Fenster sein und wird mit dem erzeugen eines neuen gelöscht. Bei Treffer erhöht sich der score um 10 plus die Anzahl an vorher getroffener Gegner mit dem gleichen Projektil. Projektile werden immer aus der Richtung geschossen, in die der Spieler Schaut.
E: Eine temporäre Unverwundbarkeit (zu sehen durch die Hellblaue Farbe) gefolgt von einer Abklingzeit (zu sehen durch die Gelbe Farbe). Während der Unverwundbarkeit kann einen der BossGegner noch mit Kontakt Angreifen.
R: Vier Pinke Rechtecke erscheinen um den Spieler, welche Gegner treffen und nach kurzer Zeit wieder verschwinden. Pro Gegner wird der Score um 15 ehröht.
TAB und T: Drehen den Spieler entweder im oder gegen den Uhrzeigersinn.
Dieses Projekt gab mir guten eindruck wozu ich fähig bin. In Zukunft möchte ich mir das Programmieren in Unity aneignen.

-8damenproblem
Diese Webanwendung repräsentiert das Damenproblem (https://de.wikipedia.org/wiki/Damenproblem). Es gillt 8 Damen auf ein Schachbrett zu platzieren, ohne dass diese sich gegenseitig in den weg der jeweiligen Laufbahnen kommen.
Oben gibt es einen Knopf zum neustarten wenn man etwas falsch platziert hat. Sobald 8 Damen in einer der richtigen Weisen auf dem Spielbrett platziert wurden wird eine Siegesnachricht erzeug.
Fast alles auf der Seite wird Programmatisch erzeugt. Dies war eine Zusatzaufgabe meiner Lehrkraft im Unterricht Internetanwendungen während der Mittelstufe.

-Schach
Eine Webanwendung, auf der sich Schach Spielen lässt. Geschrieben habe ich den Code während eines Vierwöchigen Praktikums. Der Code ist schon etwas älter und Ich würde ihn heutzutage anders schreiben.
bekannte Fehlerquellen sind auf der Seite gelistet. Ansonsten ist das Spiel vollkommen funktionstüchtig. Ich konnte hier auf viele kreative Wege lernen logische Dinge in Javascript umzusetzen.
