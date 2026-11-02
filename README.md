# WERTGARANTIE Punkte-Jagd (Becker + Flöge)

Statische Aktionsseite, eine einzige Datei: `index.html`. Kein Build nötig.
Veröffentlicht über Vercel, jeder Commit auf `main` geht automatisch live.

## Zahlen aktualisieren

Alle Werte stehen im Block `CONFIG` am Ende der `index.html`:

- `points` – aktueller Punktestand der Filiale
- `prev`   – Stand vom letzten Dienstag (daraus entsteht "+X diese Woche" und die "Filiale der Woche")
- `v`      – Anzahl der teilnehmenden Verkäufer der Filiale
- `asOf`   – Datum, das unter dem Ranking steht, z. B. 'Dienstag, 03.11.2026'
- `demo`   – auf `false` setzen, dann verschwindet der Hinweis "Vorschau mit Beispielwerten"

Direkt auf GitHub bearbeiten: `index.html` öffnen, Stift anklicken, ändern, "Commit changes".
Vercel veröffentlicht die neue Version nach etwa einer Minute.

## Vor dem Start am 15.11.2026

- `demo: false`
- alle `points` und `prev` auf `0`
