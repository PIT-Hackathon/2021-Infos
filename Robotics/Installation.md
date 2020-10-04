# Installationsanleitung
Diese Installationsanleitung beschreibt die Installation der erforderlichen (Python) Komponenten zur Programmierung von Lego Boost über Bluetooth LE. Sie gilt (in Teilen) für Windows und/oder Linux und sollte in etwas abgewandelter Form auch für macOS funktionieren.
## Python installieren
Grundvoraussetzung zur Programmierung mit Python ist die Installation der Programmiersprache in der aktuellen Version 3.8.
### Windows
Unter Windows (10) erfolgt die Installation besonders einfach über den Microsoft Store. Diesen startet man entweder manuell über das Windows Startmenü oder über die PowerShell bzw. die Eingabeaufforderung. Dort gibt man **python** als Befehl ein. Ist Python nicht installiert, so öffnet sich der Microsoft Store und bietet direkt die Installation von **Python 3.8** an.
### Linux
Die Installation von Python unter Linux ist meistens nicht erforderlich, da es sehr oft bereits installiert ist und von anderen Komponenten des Systems verwendet wird. Die installierte Version kann man in der Shell/Kommandozeile prüfen:
```bash
python --version
```
Sollte Python nur in einer älteren Version (< 3.8) installiert sein, so installiert man das Paket über die in Linux integrierte Paket- und Softwareverwaltung nach, was je nach Distribution anders verlaufen kann.
## PIP aktualisieren
Zu Python gehört der Paketmanager **PIP**, um weitere Bibliotheken nachzuladen und zu installieren. Zumindest unter Windows ist dieser nicht (ganz) aktuell und sollte vor der ersten Verwendung auf den aktuellsten Stand gebracht werden.
