# Home-Lab

Also... ich kenne mich noch nicht so gut aus mit Servern, wie sie miteinander interagieren, wie man sie sichert und wie man sie bedient. Dieses Home-Lab soll mir als Einstieg in diesen Teilbereich der Informatik dienen. Im Repo werde ich dokumentieren was ich mache.

Zusammen mit einem LLM habe ich einen Plan für ein Home-Lab erstellt (auf Basis von menschlichen Emopfehlungen). Der Plan sieht wie folgt aus: 

1. Virtuellen Server aufsetzen:
   - Ubuntu Server als virtuelle Maschine mit VirtualBox erstellen
   - System aktualisieren und überprüfen ob der Server korrekt läuft

2. Remote-Zugriff einrichten:
   - IP-Adresse des Servers herausfinden
   - Von Windows per SSH auf den Server zugreifen
   - Grundlegende Linux-Befehle zur Serververwaltung kennenlernen

3. Netzwerk verstehen:
   - IP-Adresse, Subnetz, Gateway und DNS untersuchen
   - Verstehen, wie Ports und Netzwerkdienste funktionieren
   - Überprüfen, welche Dienste auf dem Server erreichbar sind

4. Server absichern:
   - SSH-Key-Authentifizierung einrichten
   - Unnötige SSH-Zugriffsmöglichkeiten deaktivieren
   - Benutzer und Berechtigungen kennenlernen
   - Firewall einrichten und nur notwendige Verbindungen erlauben

5. Docker einrichten:
   - Docker und Docker Compose installieren
   - Images, Container, Ports und Volumes kennenlernen
   - Einen ersten Dienst als Container betreiben.

6. Monitoring einrichten:
   - Uptime Kuma mit Docker Compose betreiben
   - Überwachen, ob Dienste erreichbar sind
   - Logs und Linux-Werkzeuge verwenden, um den Zustand des Servers zu untersuchen

7. Backup und Wiederherstellung einrichten
   - Einen einfachen Backup-Prozess erstellen
   - Backups automatisieren
   - Testdaten löschen und aus einem Backup wiederherstellen

8. Troubleshooting üben:
   - Einen Dienst absichtlich stoppen oder falsch konfigurieren
   - Den Fehler mithilfe von Logs, Netzwerk- und Docker-Werkzeugen untersuchen
   - Ursache finden, Problem beheben und Lösungsweg dokumentieren.
