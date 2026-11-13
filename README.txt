PREMIUM STOPPUHR – INSTALLATION

Dateien:
- index.html: die Stoppuhr
- manifest.webmanifest: App-Metadaten
- sw.js: Offline-Speicherung (Service Worker)
- icon.svg: App-Symbol

WICHTIG:
Für die Installation als iPhone-Web-App und den Offline-Betrieb muss die App über HTTPS bereitgestellt werden.
Das bloße Öffnen von index.html als lokale Datei reicht auf iPhone nicht aus.

Einfacher kostenloser Weg mit GitHub Pages:
1. Erstelle oder melde dich bei github.com an.
2. Erstelle ein neues öffentliches Repository, z.B. "stoppuhr".
3. Lade alle vier Dateien (index.html, manifest.webmanifest, sw.js, icon.svg) in das Hauptverzeichnis hoch.
4. Öffne im Repository Settings > Pages.
5. Wähle "Deploy from a branch", Branch "main", Ordner "/ (root)", dann Save.
6. Warte, bis GitHub Pages eine HTTPS-Adresse anzeigt.
7. Öffne diese Adresse auf dem iPhone in Safari.
8. Tippe auf Teilen > Zum Home-Bildschirm hinzufügen.
9. Falls angeboten, aktiviere "Als Web-App öffnen", dann Hinzufügen.
10. Öffne die Stoppuhr einmal bei bestehender Internetverbindung. Danach sollte sie offline verfügbar sein.

Hinweis:
Die Stoppuhr misst präzise während die Web-App aktiv ist. iOS kann Web-Apps im Hintergrund anhalten.
Für eine Zeitmessung, die zuverlässig bei gesperrtem Bildschirm oder längerer Hintergrundnutzung weiterläuft, ist eine native iOS-App besser geeignet.
