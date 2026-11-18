# Treppenhausreinigung Martina Hoffmann

Statische, responsive Website ohne Build-Schritt, Tracking, Cookies oder externe Laufzeit-Abhängigkeiten.

## Vor Veröffentlichung: Basis-URL ersetzen

Veröffentlichte Website: `https://varenrook.github.io/treppenhausreinigung-martina-hoffmann/`

Diesen String projektweit durch die endgültige, mit `/` endende GitHub-Pages-URL ersetzen. Betroffene Stellen:

- `index.html`: Canonical, `og:url`, `og:image`, JSON-LD `url` und `image`
- `impressum.html` und `datenschutz.html`: Canonical
- `robots.txt`: Sitemap-URL
- `sitemap.xml`: alle `<loc>`-Einträge

Prüfung: Vor dem Veröffentlichen kontrollieren, dass alle kanonischen URLs auf die oben genannte Pages-Adresse zeigen.

## GitHub Pages

1. Ordnerinhalt in das Repository übernehmen und Platzhalter ersetzen.
2. **Settings → Pages → Build and deployment → Deploy from a branch** wählen.
3. Branch und Ordner festlegen (typisch `main` und `/ (root)`).
4. Nach dem Deployment Canonical, OG-Bild, `robots.txt` und `sitemap.xml` unter der echten URL prüfen.

## Rechtliches und Bilder

Impressum und Datenschutz sind konservativ für den statischen Stand formuliert. Unternehmensangaben (z. B. Rechtsform, USt-ID, Register-/Berufsangaben, falls vorhanden) müssen geprüft werden; eine individuelle rechtliche Prüfung wird empfohlen. Bei späterer Ergänzung von Analyse, Formular, Karte, externen Fonts oder Diensten ist die Erklärung anzupassen.

Die drei lokalen Bilder wurden mit Erlaubnis der Eigentümerin von `alltagshilfe-premiumcare.de` übernommen. Zur Laufzeit gibt es keine Anfrage an die Quellwebsite.
