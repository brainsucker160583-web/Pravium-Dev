# Pravium Dev
Kostenbewusster Cloud-Coding-Agent (im Aufbau).

## Aktueller Stand
- Bestehendes Browser-Spiel bleibt in `index.html`.
- `dev/index.html`: mobilfreundliche Auftragsannahme via GitHub Issues; benötigt GitHub-Login.
- `.github/workflows/pravium-dev.yml`: GitHub Actions verarbeitet neue Aufträge **nur dann**, wenn sie vom Repository-Eigentümer stammen. Externe Issues führen keinen Agentencode aus.
- Noch **keine** eigenständige KI-Codegenerierung. Ein kostenloses KI-Modell und sicherer Pull-Request-Workflow werden als nächstes eingerichtet.
- Keine Zahlungsdaten oder API-Schlüssel im Frontend ablegen. API-Schlüssel ausschließlich als GitHub Actions Secret einrichten.
- Keine automatischen Code-Merges und keine unkontrollierte Ausführung KI-generierter Shell-Befehle.

## Ausprobieren
GitHub Pages /dev/ öffnen, Auftrag formulieren, auf GitHub bestätigen, Issue und Action-Lauf kontrollieren.

## Kosten
GitHub Free besitzt Limits für Actions. Zusätzliche KI-Dienste können eigene Kontingente und Konditionen haben; dieses Projekt aktiviert keinen bezahlten KI-Dienst.
