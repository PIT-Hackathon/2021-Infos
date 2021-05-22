# Installationsanleitung
Diese Installationsanleitung beschreibt die Installation der erforderlichen (Python) Komponenten zur Programmierung von Lego Boost über Bluetooth LE. Sie gilt (in Teilen) für Windows und/oder Linux und sollte in etwas abgewandelter Form auch für macOS funktionieren.
## Python installieren
Grundvoraussetzung zur Programmierung mit Python ist die Installation der Programmiersprache. Hierbei kommt es auf das eingesetzte Betriebssystem an, ob und in welcher Version Python zur Verfügung steht; bei Linux und auch macOS ist Python in der Regel bereits installiert - möglicherweise jedoch nur in einer älteren Version (2.x).

Zur Zeit (Oktober 2020) ist die Python-Version 3.9.0 aktuell, wobei diese Version nicht zwingend notwendig ist, um mit den Robotics-Projekten zu beginnen. Älter als Version 3.6 sollte Eure Python-Installation jedoch auch nicht sein; zumindest haben wir während unserer Vorbereitungen auf den Hackathon aktuelle(re) Python-Versionen verwendet und die Anleitung(en) darauf zugeschnitten.
### Windows
Unter Windows (10) erfolgt die Installation besonders einfach über den Microsoft Store. Diesen startet man entweder manuell über das Windows Startmenü oder über die PowerShell bzw. die Eingabeaufforderung. Dort gibt man **python** als Befehl ein. Ist Python nicht installiert, so öffnet sich der Microsoft Store und bietet direkt die Installation von **Python 3.9** an.
### Linux
Die Installation von Python unter Linux ist meistens nicht erforderlich, da es sehr oft bereits installiert ist und von anderen Komponenten des Systems verwendet wird. Die installierte Version kann man in der Shell/Kommandozeile prüfen:
```bash
python --version
```
Sollte Python nur in einer älteren Version (< 3.6) installiert sein, so installiert man das Paket über die in Linux integrierte Paket- und Softwareverwaltung nach, was je nach Distribution anders verlaufen kann. Unter Linux nennt sich das Paket meist **python3**, um eine einfache Unterscheidung zur Vorversion (2.x) zu ermöglichen.

In diesem Zusammenhang sei auf weitere Lektüre wie bspw. zu [pyenv](https://realpython.com/intro-to-pyenv/) verwiesen oder auch [diesen Artikel](https://therafman.wordpress.com/2018/12/13/upgrade-to-python-3-7-and-make-it-the-default-version-in-any-linux-ubuntu-based-distributions/), der u.a. die Installation von Python 3.x auf einem Ubuntu Linux beschreibt. Andere Linux-Distributionen, z.B. Manjaro Linux, bringen bereits eine aktuelle Version von Python mit, sodass Ihr Euch um eine Installation nicht zu kümmern braucht.
## PIP aktualisieren
Zu Python gehört der Paketmanager **PIP**, um weitere Bibliotheken nachzuladen und zu installieren. Zumindest unter Windows ist dieser nicht (ganz) aktuell und sollte vor der ersten Verwendung auf den aktuellsten Stand gebracht werden. Dies erfolgt sowohl unter Windows als auch unter Linux mittels der Kommandozeile (Terminal, Eingabeaufforderung, PowerShell):
```bash
python -m pip install --upgrade pip
```
## Python-Bibliothek für die Programmierung von Lego Boost installieren
Nun kann man PIP verwenden, um die Python-Bibliothek für die Programmierung von Lego Boost zu installieren. Dies erfolgt sowohl unter Windows als auch unter Linux mittels der Kommandozeile (Terminal, Eingabeaufforderung, PowerShell):
```bash
pip install -U pylgbst
```
## Bluetooth-LE-Bibliothek für Python installieren
Die gerade installierte Bibliothek kann mehrere verschiedene andere Bibliotheken verwenden, um mittels Bluetooth Low Energy mit dem Move Hub des Lego Boost zu "sprechen". Wir installieren hier die Bibliothek **PyGatt**, was sowohl unter Windows als auch unter Linux mittels der Kommandozeile (Terminal, Eingabeaufforderung, PowerShell) erfolgt:
```bash
pip install pygatt
```
Mittels dieser Bibliothek kann Python das bereits auf der [Startseite](README.md) angesprochene USB Bluetooth Dongle ("BlueGiga") ansprechen. Eine zusätzliche Installation von Treibern ist nicht notwendig, da sowohl Windows als auch Linux (zumindest neuere Kernel) dieses Dongle sofort automatisch erkennen und verwenden können.

## Testen
Nach erfolgter Installation der obigen Komponenten kann man direkt mit einem Testprogramm loslegen, um die grundsätzlichen Funktionen des Lego Boost zu testen. Sollte man bspw. den Roboter "Vernie" aus den Lego-Bausteinen zusammengebaut haben, kann man mittels der Datei **demo.py** dessen Funktionen testen. Diese Datei (und vieles andere) kann man auf der Webseite der PyLgBst-Bibliothek finden, die Ihr in der Link-Sammlung auf der [Startseite](README.md) finden könnt.
