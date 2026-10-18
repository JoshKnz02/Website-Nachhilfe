# Mathe-Nachhilfe

Statische Website ohne Build-Schritt und ohne externe Ressourcen. Dateien: `index.html`, `impressum.html`, `datenschutz.html`, `style.css`, `favicon.svg`.

## Platzhalter

Vor der Veröffentlichung müssen diese Platzhalter in allen HTML-Dateien ersetzt werden:

`{{NAME}}`, `{{STRASSE}}`, `{{PLZ_ORT}}`, `{{EMAIL}}`, `{{TELEFON}}`, `{{PREIS_ONLINE}}`, `{{PREIS_VOR_ORT}}`

Kontrolle: `grep -rn "{{" *.html` darf nichts mehr finden.

## Vorschau lokal

`python3 -m http.server 8000` im Projektordner, dann `http://localhost:8000` öffnen.

## Veröffentlichen mit GitHub Pages

Repository-Einstellungen, Bereich Pages: Quelle "Deploy from a branch", Branch `main`, Ordner `/ (root)`.

## Hinweis

In diesem Repo (öffentlich) keine Kundendaten, Namen von Schülerinnen und Schülern oder Korrespondenz ablegen.
