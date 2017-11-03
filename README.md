# Einführung in Docker

Die Vorlesungsfolien sind unter
[https://n2o.github.io/introduction-to-docker](https://n2o.github.io/introduction-to-docker)
erreichbar.

In diesem Repository finden sich die Dateien, die während der Vorlesung beim
Live-Coding entstanden sind. In der Mediathek finden Sie dazu auch eine
Aufzeichnung dieser Vorlesung.

Hier sind drei Beispiele eingebaut, die in den nächsten Sections beschrieben
werden.

### java

In dem Ordner `java` finden Sie ein Beispiel, wie man ein Docker-Image nehmen
kann, welches das aktuelle JDK beinhaltet. Dieses JDK wird dann verwendet, um
ein einfaches HelloWorld auszugeben.

### http

Unter `http` finden Sie ein einfaches Beispiel, wie man einen Webserver starten
kann, seine eigenen HTML-Dateien einbinden kann und diese dann im NGINX
darstellen lassen kann.

### docker-compose

Als letztes haben wir docker-compose kennengelernt, womit wir u.A. einen
Python-Webserver gestartet haben, der einen Wert in einer redis-Instanz erhöht.
Diesen Service können Sie mit folgenden Befehl aus diesem Verzeichnis heraus
starten:

    docker-compose up
    
Dafür müssen Sie docker-compose installiert haben. Der Webservice ist dann unter
[http://localhost:5000](http://localhost:5000) erreichbar.
