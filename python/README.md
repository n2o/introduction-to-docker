# Mini-Webanwendung

Hier haben wir ein Python-Skript, welches den Webserver 'flask' startet, sich
mit dem Key-Value-Store 'redis' verbindet und den Counter für 'hits' bei jedem
Besuch um eins erhöht.

Die Abhängigkeiten von Python liegen in der `requirements.txt`-Datei und müssen
installiert werden, was im Dockerfile auch mit dem `pip`-Befehl geschieht.
Anschließend wird der Webserver gestartet und ist unter dem Port 5000 zu
erreichen.

Diese Image wird mit docker-compose gestartet und erzeugt auch einen
entsprechenden Container, in dem redis läuft.
