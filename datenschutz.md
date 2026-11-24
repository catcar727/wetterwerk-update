# Datenschutzhinweis – WetterWerk

Stand: 24. November 2026 · gilt für die Android-App WetterWerk (de.hitzler.wetterwerk), WetterWerk Watch und die Widgets.

## Kurz gesagt
- WetterWerk hat **kein Konto, keine Werbung, kein Tracking und keine Analyse-Dienste**.
- Alle Einstellungen, Orte und zwischengespeicherten Wetterdaten bleiben **nur auf deinem Gerät**.
- Damit Wetter, Karte und Warnungen funktionieren, schickt die App Anfragen an die unten genannten Dienste. Dabei sehen diese Dienste – wie bei jedem Webseitenaufruf – deine **IP-Adresse** und den angefragten Ort.

## Verantwortlich
Christian Hitzler (privat entwickelte App). Kontakt über die Feedback-Funktion in der App (Einstellungen → Über → Feedback).

## Welche Daten wohin gehen
| Zweck | Dienst | Was übertragen wird |
|---|---|---|
| Vorhersage, Regen, Luft & Pollen, Ortssuche | Open-Meteo (open-meteo.com, Schweiz/EU) | Koordinaten des Ortes (auf ca. 10 m gerundet), Suchbegriff, IP-Adresse |
| Unwetterwarnungen | Bright Sky (brightsky.dev) mit Daten des Deutschen Wetterdienstes | Koordinaten, IP-Adresse |
| Radar und Warnkarte | DWD GeoServer (maps.dwd.de), RainViewer (rainviewer.com) | angezeigter Kartenausschnitt, IP-Adresse |
| Grundkarte | OpenStreetMap (tile.openstreetmap.org) | angezeigter Kartenausschnitt, IP-Adresse |
| Ortsname zur GPS-Position | Android-Ortsdienst (Geocoder, je nach Gerät Google), ersatzweise OpenStreetMap Nominatim | Koordinaten, IP-Adresse |
| Update-Prüfung | GitHub (github.com, raw.githubusercontent.com) | IP-Adresse, keine Gerätedaten |
| Home Assistant (nur wenn eingerichtet) | dein eigener Home-Assistant-Server | dein Zugriffstoken – nur an die von dir eingetragene Adresse |

## Standort
- GPS wird nur genutzt, wenn du es erlaubst. Die genaue Position verlässt das Gerät nur als Koordinaten in den Wetteranfragen oben.
- „Standort im Hintergrund“ ist **aus**, bis du es einschaltest. Dann wird die Position für Widgets und Warnungen auch bei geschlossener App bestimmt.
- Es wird **kein Bewegungsverlauf** gespeichert – nur die letzte Position und der Ortsname.

## Auf dem Gerät gespeichert
Einstellungen, gespeicherte Orte, letzte Position, zwischengespeicherte Wetter- und Kartendaten, ggf. Home-Assistant-Adresse und -Token. Alles wird gelöscht, wenn du die App-Daten löschst oder die App deinstallierst.

## Feedback
Feedback wird nur gesendet, wenn du es selbst über das Teilen-Menü, WhatsApp oder E-Mail verschickst. Geräteinfos (Modell, Android-Version) hängen nur an, wenn der Schalter dafür an ist. Für den Versand gelten die Bedingungen des gewählten Messengers.

## Berechtigungen
Standort (Wetter am aktuellen Ort), Benachrichtigungen (Regen-Alarm, Warnungen, Statusleiste), Internet, Start nach Neustart (Hintergrund-Updates), Akku-Optimierung umgehen (zuverlässige Widgets), Apps installieren (nur für Updates, die du selbst bestätigst).

## Deine Rechte
Du kannst jederzeit Berechtigungen entziehen, Daten löschen (App-Info → Speicher → Daten löschen) und nach der DSGVO Auskunft, Berichtigung oder Löschung verlangen. Bei den genannten Diensten gelten deren eigene Datenschutzerklärungen. Beschwerden sind bei einer Datenschutz-Aufsichtsbehörde möglich, z. B. dem Landesbeauftragten für Datenschutz Baden-Württemberg.
