Projekt-Demo-Link: jksd.de/game

Hauptmenu:

HTML Seite mit grundlegender CSS Formatierung
dient ausschließlich der Weiterleitung (da kurze URL)

Spiel:

Verwendete Module: Node.js, Express, Socket

Spielelogic:

- Alle Spieler sind geometrische Funktionen einer Klasse mit spzifischen Eigenschaften (Position, Name, Farbe, etc.)
- Die Karte ist eine 2 Dimensionale Ebene, auf welche sich die Spieler bewegen können. Diese ist nach außen begrenzt, sodass die Spieler nicht das Spielfeld verlassen können.
- Das Multiplayer Feature gelingt duch die Kombination mit einem Socket Server, welcher die Position der Spieler und die der Projetike handhabt.
- Die Steuerung wurde sowohl für den Gebrauch am Hand als auch am PC implementiert.
- Hierfür werden die Tasten w, a, s, d abgerufen bzw. bei Handy die Position der beiden Joysticks
- Projektile werden automatisch in Schussrichtung (Spielerrichtung) mit einer Geschwindigkeit "abgefeuert"
- Die Collision der Projektile mit den Spielern lässt sich mittels einer Mathematischen Funktion berechnten, welche jedoch dur die "langsamen" Server der Hosters meistens leider nur unzureichend funktioniert. Bei einem korrekt registierten Treffer, wird der jeweilige Spieler elimieniert und vom Spielfeld entfernt.

Development Team:

Spieleentwicklung: Johannes K.
Hauptmenuentwickling: Jonas P., Oliver T.
BugFinding: Jonas P., Tim R., Oliver T., Johannes K.
Elementdesgin: Tim R.
BugFixes: Johannes K.

Besondere Danksagung an:

Willie Lawrence, David da Silva Contín, Anatoliy K.

Coming Soon:

- Lebensanzeige
- Respawn
- Startmenü
- Punkteanzeige
- weitere Texturen für Spielfigur und Spieloberfläche



