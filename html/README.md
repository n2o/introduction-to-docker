# Webserver

Wir kopieren mit dem ersten Befehl im Dockerfile alle Dateien in diesem
Verzeichnis in den Container.

Das Image kann dann mit dem Befehl gebaut werden:

    docker build -t mynginx .
    
Und der Webserver wird mit dem Befehl gestartet:

    docker run --rm -p 80:80 mynginx
    
Unter [http://localhost](http://localhost) sehen wir nun die Ausgabe unserer
index.html im NGINX Webserver.
