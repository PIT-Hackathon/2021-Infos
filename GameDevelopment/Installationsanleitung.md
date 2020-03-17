# Allgemeine Installationsanleitung GameDevelopment

Für die Teilnahme am diesjährigen Hackathon im Bereich Game Development geben wir eine gewisse Ausstattung an Software vor, in die sich Mentoren eingearbeitet haben und so bei Fragen oder Problem schneller Hilfestellung bieten können. Natürlich könnt ihr diese auch nach eueren Wünschen anpassen oder komplett andere Software verwenden. Sicher können auch hier dann die Mentoren euch mit Rat zur Seite stehen, aber wahrscheinlich nicht so schnell (auch wir müssen uns immer wieder einarbeiten)

---
### Windows 10
Das Betriebssystem auf dem wir arbeiten werden.

---
### VM-Ware Player
Ist ein Programm mit dem man andere Betriebsysteme virtuell unter Windows 10 laufen lassen kann. Diesse Programm verwenden wir um das Backend (den OpenSource Multiplayer Server Nakmama der unter Linux und Docker läuft) auf einem Windows Rechner lokal starten zu können 

---
## Ubutu 18.04
Ubuntu wird benötigt um lokal den Nakama Multiplayer Server laufen zu lassen, was einen bei der lokalen Entwicklung von sehr unterstützt.
Verwendet wird hier die Version 18.04.1 von Ubuntu. Dies ist ein kostenloses Linux-Betriebssystem.

Dowload: [Link](https://www.ubuntu.com/#download)

### Anleitung
* in VM-Ware Player eine neue Maschine erzeugen und das Image von Ubuntu 18.04.1 als Basisimage auswählen. Dann noch einen gut zugänglichen Ordner als Installationsort für den virtuellen Rechner aussuchen. Dann die geführet Installation beginnen: 
  * Die richtige Sprache einstellen (Deutsch)
  * (Wichtig) das richtig Keyboard-Layout einstellen (Deutsch)
  * [ Install Ubunutu ] auswählen durch [Enter]
  * [ Network connections ] mit [Enter] bestätigen
  * [ Configure proxy ] mit [Enter] bestätigen
  * [ Configure Ubuntun archive mirror ] mit [Enter] bestätigen
  * [ Dateisystem einrichten ] mit [Enter] bestätigen 1x
  * [ Dateisystem einrichten ] mit [Enter] bestätigen 2x
  * [ Dateisystem einrichten ] mit [Enter] bestätigen 3x
  * [ Installation starten ] mit [Enter] bestätigen
  * [ Benutzer anlegenBer ]
  * [ optionale Software auswählen] hier docker mit [Space] auswählen dann auf Done mit [Enter] bestätigen

* Installation beginnt. Neustarten, wenn Installation abgeschlossen ist. 
* Dananch in der Konsole des Servers mit euerem Benutzernamen und Passwort anmelden.
* System aktualisieren mit folgendem Kommando `sudo apt update`
* System upgraden mit `sudo apt upgrade`, Sicherheits abfrage mit [Enter] bestätigen
* System neu starten mit `sudo reboot`
* Kommando `ifconfig`ausführen und die IP-adreese aufschreiben, welche folgendes Muster hat: 192.168.160.xxx

---
## Git installieren
Git ist die Versionsverwaltung, mit der wir unseren Programmcode verwalten, ihn mit anderen teilen können und die es uns ermöglicht mit mehrere Personen zusammen ein Softwareproject zu entwickeln.

Download: [Link](https://git-scm.com/)

### Anleitung
* Installationsdatei starten
* Bei "Information" [next]
* Bei "Select Destination Location" Verzeichnis festlegen (C:\Program Files\Git) dann [next]
* Bei "Select Components" [next]
* Bei "Select Start Menu Folder" [next]
* Bei "Choosing the default editor used by Git" "Use Visual Studio Code as Git's default editor" dann [Next]
* Bei "Adusting your Path environment" [Next]
* Bei "Choosing the SSH executable" [Next]
* Bei "Choosing HTTPS transport backend" [Next]
* Bei "Configuring the line ending conversions" [Next]
* Bei "Configuring the terminal emulator to use with Git Bash" [Next]
* Bei "Configuring extra options" [Next]

---
## Docker-Compose

### Anleitung
* Windows-Taste drücken
* "Git Bash" eingeben und Git Bash starten
* Folgendes Kommando eingeben `ssh username@192.168.160.xxx` wobei xxx die Nummer ist die ihr euch aufgeschrieben habt.
* Sicherheitsabfrage mit "yes" bestätigen
* euer Passwort eingeben
* folgendes Kommando eingeben: `sudo curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose`
* folgendes Kommando eingeben: `sudo chmod +x /usr/local/bin/docker-compose`
* folgendes Kommando eingeben: `docker-compose --version`

Folgendes sollte nun in der Konsole erscheinen:

`docker-compose version 1.22.0, build f46880fe`





