# 🧮 Alltagsrechner

Sammlung praktischer Rechner für den Alltag – rein clientseitig, kein Backend, keine Daten werden übertragen.

**Live:** [https://Michdo93.github.io/alltagsrechner/](https://Michdo93.github.io/alltagsrechner/)

## Enthaltene Rechner

### 💼 Brutto-Netto-Rechner
Berechnet das Nettogehalt auf Basis des deutschen Steuerrechts (§ 32a EStG, Stand 2024).

- Alle 6 Steuerklassen (I–VI)
- Kirchensteuer (8 % Bayern/BaWü, 9 % andere Bundesländer)
- Kinderfreibeträge (0–3)
- GKV-Zusatzbeitrag (konfigurierbar)
- Kranken-, Renten-, Arbeitslosen- und Pflegeversicherung
- Solidaritätszuschlag
- Effektiver und Grenzsteuersatz
- Visuelle Abzugsquote

### 📅 Datum & Kalenderrechner
- **Countdown** bis zu einem Datum (z. B. Urlaubsbeginn)
- **Tagesdifferenz** zwischen zwei Daten inkl. Arbeitstage
- **Alter berechnen** mit genauen Jahren, Monaten, Tagen
- **Datum addieren / subtrahieren** (±n Tage)
- **Kalenderwoche** (ISO 8601), Wochentag, Jahrestag

### % Prozent & Dreisatz
- **Prozentrechner** – 4 Modi: X% von Y / Grundwert / Prozentualer Anteil / Änderung in %
- **Rabattrechner** – Endpreis und Ersparnis bei Prozentrabatt
- **MwSt-Rechner** – Brutto↔Netto, 19 % / 7 % / 0 %
- **Dreisatz** – wenn A→B, was ist C→?
- **Trinkgeldrechner** – 5/10/12/15/20 %, pro Person aufteilen

### ⚡ Energie & Strom
- **Stromkostenrechner** – Arbeitspreis + Grundpreis → Jahres-/Monats-/Tageskosten
- **Gas m³ ↔ kWh** – Umrechnung via Brennwert (Hs) und Zustandszahl (Z)
- **Gerätekosten** – Watt × Stunden → kWh und Kosten
- **Anbieterwechsel** – aktueller vs. neuer Anbieter, Einsparpotenzial

## Technologie

- **Reines HTML/CSS/JavaScript** – kein Framework, kein Build-Tool
- Alle Berechnungen laufen lokal im Browser
- Responsive Design (Mobile + Desktop)
- Google Fonts: Inter + Outfit

## Deployment (GitHub Pages)

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Michdo93/alltagsrechner.git
git push -u origin main
```

Repository → **Settings → Pages → Source: main / root** → Save

## Struktur

```
alltagsrechner/
├── index.html              ← Startseite / Übersicht
├── css/style.css           ← Design-System (Dunkelgrau + Orange)
├── js/nav.js               ← Aktiver Navigationslink
└── pages/
    ├── brutto-netto.html
    ├── datum.html
    ├── prozent.html
    └── energie.html
```
