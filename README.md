# DriveLog Web V1

Mobile-first Web-App/PWA-Prototyp für iPhone/iPad.

## Testen
Die `index.html` benötigt einen Webserver, damit Browser-Standortzugriff zuverlässig funktioniert. Für einen schnellen Test kann der Ordner auf einen statischen HTTPS-Host gelegt werden.

## Bereits enthalten
- mobile App-Oberfläche
- lokale Speicherung via localStorage
- Kilometerstand
- manuelle Fahrtenerfassung
- GPS-Erfassung im Browser
- automatische Start-/Endposition innerhalb der geöffneten Seite
- Monatsübersicht
- CSV-Export
- JSON-Backup

## Bewusste Einschränkung
Die aktuelle Web-V1 verwendet bei GPS-Fahrten nur die Luftlinienentfernung als Fallback und zeigt Koordinaten statt echter Adressen. Für die nächste Version werden Reverse-Geocoding und ein Routing-Dienst angebunden. Vollautomatische Hintergrund-Fahrterkennung wird später in der nativen iPhone-App umgesetzt.
