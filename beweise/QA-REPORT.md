# QA-Report: lechcode-test

**Gesamtampel: 🟡 GELB** · 0 rot / 9 gelb / 7 grün · 13.07.2026 00:47 · Dauer 18 s · lc-qa.py

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
- **iOS-Zoom mein-bereich.html**: 2 Eingabefeld(er) mit font-size < 16px

## 🟢 GRÜN
- **Interne Links & Assets**: alle Verweise in 5 Seiten existieren
- **Externe Requests**: keine (cookiefrei/0 Tracker bestätigt)
- **OG-Tags**: index/vorschau vollständig
- **Grep-Fallen & noindex**: clamp/calc sauber, noindex gesetzt
- **Bild-Budget**: kein Einzelbild > 250 KB
- **Burger-Menü index.html**: öffnet, navigiert, schließt
- **Playwright-Screenshots**: 5 Seiten × 3 Breiten → qa-shots/
