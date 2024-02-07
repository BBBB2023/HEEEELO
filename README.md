# Befehlsreferenz

## Terminal-Befehle

- `pwd`: Zeigt den aktuellen Pfad an.
- `cp Quelldatei Zielverzeichnis`: Kopiert eine Datei in ein anderes Verzeichnis.
- `mv AlteDatei NeuerName`: Benennt eine Datei um.
- `rm Dateiname`: Löscht eine Datei.
- `chmod Berechtigungen Dateiname`: Ändert die Dateiberechtigungen.

## Netzwerkbefehle

- `ping Zieladresse`: Überprüft die Erreichbarkeit einer Adresse.
- `nslookup Domain`: Löst den DNS-Namen in die IP-Adresse auf.
- `curl URL`: Lädt den Inhalt einer URL herunter.
- `traceroute Zieladresse`: Verfolgt den Weg zu einer Adresse.

## Systeminformationen

- `uname -a`: Zeigt Informationen zum Betriebssystem an.
- `df -h`: Zeigt die Festplattenbelegung an.
- `top`: Zeigt laufende Prozesse an.
- `free -m`: Zeigt den freien Arbeitsspeicher an.

## Docker-Befehle

- `docker run Image`: Startet einen Docker-Container.
- `docker ps`: Zeigt laufende Container an.
- `docker exec -it Container bash`: Öffnet eine interaktive Shell in einem laufenden Container.
- `docker-compose up`: Startet Dienste gemäß der Docker Compose-Datei.

## Versionskontrolle

- `svn checkout Repository-URL`: Klont ein SVN-Repository.
- `svn update`: Aktualisiert das Arbeitsverzeichnis mit den neuesten Änderungen.

## Weitere Tools

- `grep Muster Dateiname`: Sucht nach einem Muster in einer Datei.
- `find Startverzeichnis -name Dateiname`: Sucht nach Dateien im Dateisystem.
- `awk 'Muster' Dateiname`: Verarbeitet und extrahiert Text.

