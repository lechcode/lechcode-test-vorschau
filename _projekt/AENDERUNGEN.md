# Änderungen

## 2026-07-13 — Cache-Test: Hero-Eyebrow „& Online" wieder entfernt

**Kundenwunsch (wörtlich):**
> Cache-Test: Eyebrow oben wieder auf nur MENTAL-COACHING - MUENCHEN (ohne Online)
> Strukturiert:
> - Hero Eyebrow: Eyebrow-Text zurueck auf Mental-Coaching Muenchen ohne Zusatz

**Prüfbare Kriterien:**
- `index.html`, Hero-Eyebrow (`.eyebrow` in `.hero`): Text lautet exakt „Mental-Coaching · München" (Mittelpunkt und Umlaut beibehalten, kein „& Online" mehr).
- Andere Eyebrows und Meta-Texte bleiben unverändert (nur die Hero-Pille war betroffen).

- [x] umgesetzt

## 2026-07-13 — Hero-Eyebrow um „& Online" ergänzt

**Kundenwunsch (wörtlich):**
> Bitte aendere die Eyebrow-Zeile ganz oben von MENTAL-COACHING - MUENCHEN zu MENTAL-COACHING - MUENCHEN & ONLINE

**Prüfbare Kriterien:**
- `index.html`, Hero-Eyebrow (`.eyebrow` in `.hero`): Text lautet exakt „Mental-Coaching · München & Online" (Mittelpunkt und Umlaut beibehalten, `&` als `&amp;` kodiert).
- Nur die Eyebrow-Pille geändert — Meta-Description, OG-Description, About-Absatz und Footer sprechen bewusst weiter von „in München" bzw. „· München" (dort wurde nichts beauftragt).

- [x] umgesetzt

## 2026-07-13 — Überschrift „So arbeite ich"

**Kundenwunsch (wörtlich):**
> Bitte ändere die Überschrift im Abschnitt „So arbeite ich" von „In drei ruhigen Schritten." auf „In drei einfachen Schritten."

**Prüfbare Kriterien:**
- `index.html`, Abschnitt `#so`: `<h2>` lautet exakt „In drei einfachen Schritten."
- Keine weiteren Vorkommen der alten Formulierung im Projekt (Footer, JSON-LD, OG, Impressum) — geprüft: kein weiterer Treffer.

- [x] umgesetzt
