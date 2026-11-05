# Solothurn Watch Clinic – Website

Dateien
- `index.html` – Startseite (Onepage)
- `impressum.html`, `datenschutz.html`
- `support.js` – Laufzeit der Seite, muss im selben Ordner liegen
- `assets/` – Fotos als WebP (720 und 1440 px), Schriften lokal (WOFF2), Logo, Open-Graph-Bild

Hochladen: den ganzen Ordner unverändert auf den Webserver kopieren. Lokal testen über einen kleinen Webserver (z. B. `npx serve`), nicht per Doppelklick.

## Smartphone
- Alle Scroll-Effekte (seitlich fahrende Galerie, Explosionsansicht, Fortschrittslinie, Masken-Headlines) laufen auch auf dem Smartphone, mit stabiler Höhe (svh), ohne Ruckeln durch die Adressleiste.
- Leistungen: Goldlinie und Nummer aktivieren sich beim Scrollen.
- Bilder zoomen beim Einblenden sanft heraus und werden farbig.
- Vorher/Nachher-Regler: horizontal ziehen, vertikales Scrollen bleibt frei.
- Buttons geben beim Antippen nach. Cursor, Lupe und Hover-Vorschau nur mit Maus.
- Bei «Bewegung reduzieren» im System: nur sanfte Überblendungen.

## Platzhalter (vor Livegang ersetzen)
- [[INHABER]], [[RECHTSFORM]], [[UID-NUMMER]], [[HANDELSREGISTER-EINTRAG]] – Impressum
- [[BITTE PRÜFEN]] – Markenhinweis im Impressum
- [[DATUM]], [[HOSTING-ANBIETER, LAND]], [[SPEICHERDAUER]], [[FORMULAR-DIENST]] – Datenschutz
- Google-Maps-Karte lädt erst nach Klick («Karte laden»), damit ohne Einwilligung keine Daten an Google gehen
- [[WEITERE ARBEITSSCHRITTE ZENITH]] – Detailansicht Arbeit 04
- Formular: zeigt heute nur eine Bestätigung. Für den echten Versand einen Endpunkt anbinden ([[FORMULAR-ENDPUNKT]]).
- Kundenstimmen, Garantie, Preise: bewusst nicht enthalten (Preise «auf Anfrage»).

## Hinweise für den Livegang
- Schriften (Inter Tight, Instrument Serif) lokal einbinden statt über Google Fonts.
- Bilder als WebP exportieren; Open-Graph-Bild 1200×630 aus post-01 erstellen.
- Favicon aus profil.jpg in 32/180/512 px erzeugen.
