# Planungs- und Bewertungsinstrument v1.0

Lokale Webanwendung zur strukturierten Planung und Bewertung archäologischer Objektdokumentation.

Version 1.0 ist der für die Masterarbeit eingefrorene Entwicklungsstand. Weitere konzeptionelle Änderungen sollen nur bei einem tatsächlich festgestellten fachlichen oder technischen Fehler erfolgen.

## Start

`index.html` in einem aktuellen Browser öffnen. Es ist keine Installation und keine Internetverbindung erforderlich.

## Grundprinzip

Die Anwendung ist eine strukturierte Entscheidungshilfe. Sie führt von Nutzung beziehungsweise Zielnutzung über benötigte Objektinformationen, Erfassungsumfang und Datenhandlungen zur Dokumentationsform, zum Soll-Profil und anschließend zur konkreten Umsetzung beziehungsweise zum vorhandenen Bestand. Praxis- und Ist-Profil werden fachlich eingeschätzt und an denselben konkreten Soll-Anforderungen und Geltungsbereichen abgeglichen.

Das Instrument ist kein Entscheidungsautomat. Regelbasierte Orientierung hebt typische Möglichkeiten hervor; die fachliche Auswahl bleibt beim Benutzer. Praxis- und Ist-Profil werden nicht aus Verfahren, Gerät oder Projektbedingungen berechnet.

## Zentrale Regeln

- mehrere Nutzungen werden in einem gemeinsamen Entscheidungsweg zusammengeführt;
- bei derselben konkreten Anforderung und demselben Geltungsbereich gilt bei mehreren Auslösern der höchste erforderliche Mindestanspruch;
- keine Mittelwerte und keine Kompensation zwischen Qualitätsbereichen;
- Dokumentationsformen werden nicht automatisch ausgewählt; typische Formen werden nur hervorgehoben und begründet;
- eine 3D-bezogene Dokumentationsform öffnet den 3D-spezifischen Qualitätsweg;
- retrospektiv bleibt `n. b.` („nicht beurteilbar“) ein eigener Status;
- Zielkonflikte sind Hinweise und Dokumentationsmöglichkeiten, keine automatische Priorisierung;
- eine begründet akzeptierte Abweichung bleibt eine Abweichung und verlangt eine dokumentierte Begründung.

## Dateien

- `index.html` – Oberfläche
- `styles.css` – Darstellung und Drucklayout
- `app.js` – Anwendungs-, Abhängigkeits-, Migrations- und Vergleichslogik
- `instrument-data.js` / `instrument-data.json` – versionierte Wissensbasis
- `docs/` – vollständige Wissensbasis und Entscheidungslogik als HTML und PDF
- `beispiele/` – vier hypothetische Anwendungsfälle als finaler JSON-Fallzustand und Prüfbericht (PDF)


## Kompatibilität


© Ronny Weßling, 2026
