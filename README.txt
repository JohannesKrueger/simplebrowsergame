Projektfortschritt:

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
- weitere Texturen für Spielfigur und Spieloberfläche (Tim ist krank)

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
