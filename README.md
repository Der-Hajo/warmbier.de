# warmbier.de

Private Website von Hajo Warmbier: Fotos, Projekte und Links.
Live: https://warmbier.de

## Aufbau
- Statische Seiten (reines HTML mit CSS, kein Build-Skript):
  `index.html`, `impressum.html`, `datenschutz.html`, `404.html`
- `fonts/` – Schriften Archivo und JetBrains Mono (SIL Open Font License, Lizenztexte liegen dabei)
- `bilder/` – Porträt für die Startseite (verfremdete Version)
- `favicon.svg`, `favicon.ico`, `apple-touch-icon.png`, `og-image.png` – Icons und Vorschaubild
- `CNAME` – Domain für GitHub Pages (muss bleiben)

## Hosting
GitHub Pages aus dem Zweig `main`, Domain warmbier.de (DNS bei STRATO), HTTPS aktiv.

## Arbeitsweise
- `main` ist die Live-Version und geschützt.
- Änderungen nur über einen eigenen Zweig (`aenderung-JJJJ-MM-thema`) und einen Pull Request.
- Jede Änderung wird in `CHANGELOG.md` festgehalten.

## Nicht im Repository
Entwürfe, Originalfotos, Sicherungen und Zugangsdaten. Die Fotoalben liegen
passwortgeschützt auf einem eigenen Server; die Seite verlinkt nur darauf.
