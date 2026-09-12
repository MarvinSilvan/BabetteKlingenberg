# Babette Klingenberg – Relaunch-Vorschläge

Drei Design-Vorschläge zur Modernisierung von [babette-klingenberg.de](https://www.babette-klingenberg.de/), erstellt auf Basis der Texte und Bilder der bestehenden Website.

## Ansehen

- `index.html` – Übersicht mit Links zu allen drei Vorschlägen
- `proposal-1-klassisch/` – Klassisch-Elegant (Creme/Bordeaux, Serifen, nah am bestehenden Look)
- `proposal-2-atelier/` – Warmes Atelier (Editorial-Stil, Seitennavigation, Terrakotta/Olive)
- `proposal-3-galerie/` – Moderne Galerie (dunkles Theme, Masonry-Grid, bildstark)

Lokal einfach `index.html` im Browser öffnen, oder über GitHub Pages (siehe unten) live ansehen.

## GitHub Pages aktivieren (einmalig)

Damit die Vorschläge über eine echte URL erreichbar sind:

1. Repo auf GitHub öffnen → **Settings → Pages**
2. Unter „Build and deployment": Source = **Deploy from a branch**
3. Branch = `main`, Ordner = `/ (root)` → **Save**
4. Nach ca. 1–2 Minuten ist die Seite unter `https://<username>.github.io/BabetteKlingenberg/` erreichbar

## Was übernommen wurde

- **Texte**: wörtlich von der Original-Website (Vita, Meine Arbeit, Malerei, Illustration, Karten, Ausstellungen, Kontakt, Impressum-Angaben)
- **Bilder**: Original-Thumbnails aus `images/` (Logo, Portrait, Gemälde-, Illustrations- und Kartenkategorien)

## Offene Punkte / Annahmen

- **Bildauflösung**: Es wurden die auf der Live-Seite verfügbaren Thumbnails (klein, teils < 150 px) übernommen. Für den finalen Launch sollten hochauflösende Originalbilder von Babette Klingenberg eingebunden werden – aktuell wirken die Bilder in großen Kacheln entsprechend weich.
- **Kontaktformular**: Die Formulare in allen drei Vorschlägen sind rein optisch (kein Versand-Backend). Das Original nutzte ein Strato-CGI-Mailscript – für den Relaunch empfiehlt sich ein moderner Form-Service (z. B. Formspree, Netlify Forms) oder ein einfaches `mailto:`-Fallback.
- **Preise/Angebote** (Karten 2,50 €, Kalender 8,00 €) und die **Ausstellungsliste** (zuletzt 2011) stammen unverändert von der Originalseite – vor Veröffentlichung mit Babette Klingenberg auf Aktualität prüfen.
- **Impressum**: Aus Datenschutzgründen wurde die im Original genannte Technik-Umsetzerin (Drittperson) nicht in die Vorschläge übernommen; bei Bedarf im finalen Impressum ergänzen.
- Keine der drei Varianten ist als „fertig zum Livegang" gedacht – es sind Gestaltungsvorschläge zur Auswahl einer Richtung, danach folgt Feinschliff (Responsive-Test auf echten Geräten, echtes Kontaktformular, SEO/Meta-Tags, Bildoptimierung).

---
Erstellt mit Claude Code.
