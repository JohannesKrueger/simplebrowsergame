Projektfortschritt:

Projektbeschreibung:

Dieses Projekt wurde angesichts des Informatik Unterrichts Q4 entwickelt. Hierbei war die Zielsetzung, ein einfach gehaltenes Browers Game zu entwickeln, welches sowohl im Single, als auch im Multiplayer spielbar ist.


Arbeitseinteitung:

Spieleentwicklung: Johannes K.

Hauptmenuentwickling: Jonas P., Oliver T.

BugFinding: Jonas P., Tim R., Oliver T., Johannes K.

Elementdesgin: Tim R.

BugFixes: Johannes K.

Besondere Danksagung an:

Willie Lawrence, David da Silva Contín, Anatoliy K.


Hauptmenu:

HTML Seite mit grundlegender CSS Formatierung
dient ausschließlich der Weiterleitung (da kurze URL)

Spiel:

Verwendete Module: Node.js, Express, Socket

Spielelogic

alle Spieler sind geometrische Funktionen einer Klasse mit spzifischen Eigenschaften (Position, Name, Farbe, etc.)
die Karte ist eine 2 Dimensionale Ebene, auf welche sich die Spieler bewegen können. Diese ist nach außen begrenzt, sodass die Spieler nicht das Spielfeld verlassen können.
Das Multiplayer Feature gelingt duch die Kombination mit einem Socket Server, welcher die Position der Spieler und die der Projetike handhabt.
Die Steuerung wurde sowohl für den Gebrauch am Hand als auch am PC implementiert.
Hierfür werden die Tasten w, a, s, d abgerufen bzw. bei Handy die Position der beiden Joysticks
Projektile werden automatisch in Schussrichtung (Spielerrichtung) mit einer Geschwindigkeit "abgefeuert"
Die Collision der Projektile mit den Spielern lässt sich mittels einer Mathematischen Funktion berechnten, welche jedoch dur die "langsamen" Server der Hosters meistens leider nur unzureichend funktioniert. Bei einem korrekt registierten Treffer, wird der jeweilige Spieler elimieniert und vom Spielfeld entfernt.

Zuätze:

Projekt-Demo-Link: jksd.de/game

Erledigt:
- Steuerung der Spielfigur [W,S,A,D]
- Spieloberfläche [definiert durch Bidschirmgröße]
- Browserkompatibilität [Plugins. Node.js, Express]
- Multiplayer [aufgesetzer Socket Server gehostet von Heroku]
- Schießmechanismus [Objekt initialisieren mit Spielergeschwindigeit * a]
- Username [Consolenanfrage]

Was wir noch hinzufügen wollen:
- Lebensanzeige
- Respawn
- Startmenü
- Punkteanzeige
- weitere Texturen für Spielfigur und Spieloberfläche (Tim war krank)

More Fixes and Bugs:


Ingame Backgrund img

Movement
	360 Deg Movement
	Shoot diagonal (360 Deg)

Shoot interval (100ms)

Responsive webdesign

	Mobile Joystick → Movement
	Text

Start Menu with Button

healthbar Top Left

Multiplayer Killcount (Points under Name)

Fix empty Name or „null“ to anonym

Tod

	Todes Chat
	Todes Nachricht mit Restart Button

Fix Screen resolution (Map size,- Player Speed, Bulletspeed)

Clear Screen from Dead Player (remove shooting and player-hitbox(collisions)) "Collisions fixed"

Fix Multipleplayer Errors (Playercount > 2 –> Networking Errors)
