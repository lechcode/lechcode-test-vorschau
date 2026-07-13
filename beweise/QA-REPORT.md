# QA-Report: lechcode-test

**Gesamtampel: 🟡 GELB** · 0 rot / 11 gelb / 5 grün · 13.07.2026 11:08 · Dauer 69 s · lc-qa.py

## 5-Minuten-Abnahme (Mensch)
1. Alle 🔴 unten abgearbeitet? 2. Screenshots in `qa-shots/` überflogen — „würde ich das verschicken?"
3. ROT-Assets in ASSETS-LIZENZEN.md ok für Vorschau? 4. MAIL-KUNDE/VERSAND-NACHRICHT gelesen? 5. Link einmal am eigenen Handy antippen.

## 🔴 ROT (Blocker)
- —

## 🟡 GELB (prüfen/dokumentieren)
- **OG-Tags datenschutz.html**: fehlt: og:title, og:description, og:image
- **OG-Tags impressum.html**: fehlt: og:title, og:description, og:image
- **OG-Tags mein-bereich.html**: fehlt: og:title, og:description, og:image
- **OG-Tags onboarding.html**: fehlt: og:title, og:description, og:image
- **robots.txt**: fehlt oder ohne Disallow
- **impressum.html nicht verlinkt von**: datenschutz.html, mein-bereich.html, onboarding.html
- **datenschutz.html nicht verlinkt von**: impressum.html, mein-bereich.html, onboarding.html
- **ASSETS-LIZENZEN.md fehlt**: ab v2.0 Pflicht — Altprojekt? Foto-Rechte-Ampel nachziehen
- **Lighthouse**: Lauf fehlgeschlagen: untered: Chrome prevented page load with an interstitial. Make sure you are testing the correct URL and that the server is properly responding to all requests.

- **Playwright-Lauf**: page.goto: net::ERR_CONNECTION_TIMED_OUT at http://localhost:62570/datenschutz.html
Call log:
  - navigating to "http://localhost:62570/datenschutz.html", waiti
- **Playwright**: 

## 🟢 GRÜN
- **Interne Links & Assets**: alle Verweise in 5 Seiten existieren
- **Externe Requests**: keine (cookiefrei/0 Tracker bestätigt)
- **OG-Tags**: index/vorschau vollständig
- **Grep-Fallen & noindex**: clamp/calc sauber, noindex gesetzt
- **Bild-Budget**: kein Einzelbild > 250 KB
