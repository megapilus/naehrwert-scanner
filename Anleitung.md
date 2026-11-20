# Nährwert-Scanner – Einrichtung auf GitHub Pages

## Dateien (alle 6 in denselben Ordner des Repositorys)

- `index.html` – die App
- `bls_4_0_compact.json` – BLS 4.0 (Mikronährstoffe)
- `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png` – Name und Symbol für den Home-Bildschirm

## Einmalig einrichten

1. Auf github.com oben rechts **+ → New repository**.
   Name z. B. `naehrwert-scanner`, Sichtbarkeit **Public** (GitHub Pages ist im kostenlosen Konto nur für öffentliche Repositorys verfügbar). **Create repository**.
2. Auf der leeren Repository-Seite **uploading an existing file** anklicken, alle 6 Dateien hineinziehen, unten **Commit changes**.
3. **Settings → Pages** (links). Unter *Build and deployment*: Source **Deploy from a branch**, Branch **main**, Ordner **/ (root)**, **Save**.
4. 1–2 Minuten warten. Oben auf der Pages-Seite erscheint die Adresse, z. B.
   `https://DEIN-NAME.github.io/naehrwert-scanner/`

## Auf dem iPhone

1. Die Adresse in **Safari** öffnen.
2. Teilen-Symbol → **Zum Home-Bildschirm** → „Als Web-App öffnen“ eingeschaltet lassen → **Hinzufügen**.
3. Beim ersten Scan nach dem Kamerazugriff fragen lassen und **Erlauben** tippen.
   (iOS fragt bei Web-Apps manchmal nach jedem Neustart erneut – das ist normal.)
4. Unter ⚙ **Tagesbedarf** Geschlecht, Alter, Gewicht, Größe und Aktivität eintragen.

## Später aktualisieren

1. Im Repository die geänderte Datei (meist nur `index.html`) wieder über **Add file → Upload files** hochladen → **Commit changes**.
2. 1–2 Minuten warten, dann in der App ⚙ → **↻ App neu laden**.

## Datenschutz

Das Repository ist öffentlich, enthält aber nur den Programmcode und die BLS-Tabelle.
Einstellungen und Verlauf werden ausschließlich auf dem iPhone gespeichert.
Die App fragt nur Open Food Facts nach dem gescannten Strichcode.

Daten: Open Food Facts (ODbL), Bundeslebensmittelschlüssel 4.0 (Max Rubner-Institut).
