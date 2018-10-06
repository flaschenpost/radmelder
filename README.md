# Radmelder
Im Rahmen des Kampagne [Leezenstadt](https://www.leezenstadt.de) in Münster hat [@albwe](https://albwe.de) einen Melder für Probleme auf Radwegen gebaut. Die Probleme können damit gesammelt und angezeigt werden. Nutzer*innen können selbst Problemstellen melden, die dann von Redaukteur*innen im Backend gegengelesen und veröffentlicht werden. So kann ein umfassendes Bild über die Probleme auf Radwegen in Städten gemeinsam mit en Nutzer*innen erzielt werden.
## Implementierung
Folgende Dinge sind (u.a.) zur Implementierung des Radmelders nötig:
* Erstellung einer MySQL-Datenbank (Konfigurationsdatei radwege.sql)
* Legen der Dateien in ein Verzeichnis auf dem Webserver
* Website per Pflicht-HTTPS schützen (sonst funktionieren bestimmte Funktionen wie die GPS-Ortung nicht)
* Im */* der Website den Ordner *upload* für die Bilder anlegen.
* *verwaltung* per .htaccess oder ähnlichem vor der Öffentlichkeit schützen
* *php/config_example.php* und *js/config_example.js* ohne *_example* kopieren und mit den eigenen Daten füllen.

Veröffentlicht unter GNU-Lizenz (s. LICENSE).
