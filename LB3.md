#  Dokumentation LB3 Lucas Gamper 

# K1 / K2

## Persönlicher Stand

Ich habe bezüglich Docker, Microservics und Container kaum Erfahrung. Ich kenne ein wenig von der Theorie aus dem Modul 300 und ÜK 340 mehr aber auch nicht. Was genau Technisch im Hintergrund abgeht weiss ich nicht. Ich verwende zwar täglich Container wie YouTube oder Gmail und weiss, dass diese immer mehr an Popularität gewinnen, wie diese einzurichten sind weiss ich jedoch nicht. Ich bin gespannt mit Docker etwas mehr über Container zu lernen.

Da ich wie gesagt nur begrenztes Vorwissen habe, habe ich zuerst einmal die Unterlagen auf dem BSCW durchgelesen.Anschliessend habe ich mir noch ein Basic Docker Tutorial auf YouTube angeschaut.

## Einrichten

### Git bash

1. Git bash herunterladen 
2. Git bash installieren

Anschliessend wird noch das Repository auf den lokalen Computer kopiert.

$ git clone https://github.com/mc-b/M300      #Repository klonen
 
  
### GitHub Account

1. GitHub Account erstellen
2. Mit Git bash SSH Key erstellen
 $ ssh-keygen -t rsa 4096 -C "lucas.gamper@edu.tbz.ch"
3. SSH Key dem Agent hinzufügen
4. SSH Key dem GitHub Konto hinzufügen

### Virtualbox

1. Virtualbox herunterladen
2. Virtualbox installieren

### Visual Studio Code

1. Visual Studio Code herunterladen
2. Visual Studio Code installieren
3. Extensions installieren
4. Einstellungen anpassen

### Vagrant

1. Vagrant herunterladen
2. Vagrant installieren
3. Vagrant VM erstellen

### Docker

1. Docker Account erstellen auf www.hub.docker.com
2. Docker Desktop für Windows installieren (neustart benötigt)

# K3

### Geplante Umgebung:

Für die LB3 werde ich wie bei der LB2 einen Webserver aufsetzen welcher die Verwaltung der MySQL Datenbank ermöglicht. Diese beiden Container werden in einem einzigen Docker Image erstellt. Zusätzlich kommt noch phpmyadmin aus einem anderen Image um die Kombination von zwei verschiedenen Container zu ermöglichen. Ausserdem wird auf der Datenbank ein persistentes Volume erstellt und es werden Sicherheitsmassnahme und ein Monitoring umgesetzt.

# Docker Befehle

| Befehl           |Beschreibung                                                                                   |
| -----------------|:---------------------------------------------------------------------------------------------:|
| Docker run       |Startet neuen Container - Der Befehl bietet unzählige Optionen und Parameter für Konfiguration |
| Docker run -it ubuntu /bin/bash       |Erzeugt und Konfiguriert eine Virtuelle Maschine basierend auf dem Vagrantfile           |
| Vagrant ssh      |Verbindung zur VM per SSH wird hergestellt                                               | 
| Vagrant status   |Zeigt den aktuellen Status der VM an                                                     | 
| Vagrant port     |Zeigt die Weitergeleiteten Ports der VM an                                               | 
| Vagrant halt     |VM wird gestoppt                                                                         | 
| Vagrant destroy  |VM wird gestoppt und gelöscht                                                            | 



