# Änderungen

## 2026-07-15 — Neue Sektion „Mein Ort": Landsberg-am-Lech-Bild eingebaut

**Kundenwunsch (wörtlich):**
> bau bitte das bild ein und schreib dazu dass landsberg am lech die location ist von wo aus ich arbeite

**Datei:** `uploads/eingang/landsberg-am-lech-tipps-mrlxnbtj.jpg` (bild, „landsberg-am-lech-tipps.jpg")

**Prüfbare Kriterien:**
- `index.html`: neue Sektion `#ort` zwischen „So arbeite ich" (`#so`) und dem Stats-Block eingefügt. Zwei-Spalten-Layout (Bild links, Text rechts), Reveal-Animation wie bei den anderen Sektionen, Design-Tokens des Bestands (r-lg, shadow, eyebrow, .grad).
- Bild referenziert direkt den Upload-Pfad `uploads/eingang/landsberg-am-lech-tipps-mrlxnbtj.jpg` (Datei bewusst nicht verschoben — das System sortiert das Asset später ein), `alt` beschreibt Ort & Rolle, `loading="lazy"` wie im Bestand.
- Kein Text/Overlay über dem Bild (Hero-Regel), object-fit:cover, aspect-ratio 4/3.
- Neue Styles unter `/* Ort */` im bestehenden `<style>`-Block; unter 900 px Einspalten-Layout (analog Hero).
- Bewusst unangetastet: Hero-Eyebrow „Mental-Coaching · München", Meta-/OG-Description, Footer-About — der Kunde hat die Standort-Aussagen dort nicht beauftragt, das bleibt konsistent mit den vorigen Änderungsblöcken. Der Text der neuen Sektion nennt zusätzlich „online für alle, die weiter weg sind", damit die Aussage kompatibel zum bestehenden München-Auftritt bleibt.

**Offen — Team:**
- (nichts offen)

- [x] umgesetzt

## 2026-07-13 — Neupositionierung: Hero + „Kennst du das?" auf Beziehungs-/Selbstwert-Thema

**Kundenwunsch (wörtlich):**
> Hauptüberschrift (Hero-Bereich, aktuell 'Ganzheitliche Begleitung auf dem Weg zu deiner inneren Stärke.'): Ersetzen durch: Überschrift 'Du gibst in deiner Beziehung ständig dein Bestes — und fühlst dich trotzdem nie gut genug.' mit Unterzeile 'Ich begleite dich zurück zu echter Selbstsicherheit — damit du aus innerer Ruhe heraus liebst, statt aus Angst, nicht genug zu sein.'
> Abschnitt 'Kennst du das?' mit den drei Mustern (aktuell 'Erschöpft', 'Getrieben', 'Unklar'): Ersetzen durch: Einleitungssatz 'Von außen läuft die Beziehung — innen fühlst du dich trotzdem nie ganz sicher.' und drei Karten: 1) 'Nicht genug' – 'Du gibst dein Bestes, kümmerst dich, passt dich an — und trotzdem bleibt das Gefühl, nicht wirklich zu genügen.' 2) 'Angespannt' – 'Du wartest innerlich auf den nächsten Moment, in dem du enttäuschst. Das Außen bestimmt, wie sicher du dich fühlst, nicht du selbst.' 3) 'Unsicher' – 'Du zweifelst oft, ob das, was du tust oder fühlst, richtig ist. Die innere Sicherheit fehlt.'

**Prüfbare Kriterien:**
- `index.html`, Hero-`h1`: exakt „Du gibst in deiner Beziehung ständig dein Bestes — und fühlst dich trotzdem nie gut genug." (Gradient-Highlight bewusst auf „nie gut genug" gesetzt — analog zur bisherigen `<span class="grad">`-Design-Sprache).
- `index.html`, Hero-`p.lead`: exakt „Ich begleite dich zurück zu echter Selbstsicherheit — damit du aus innerer Ruhe heraus liebst, statt aus Angst, nicht genug zu sein."
- `index.html`, Sektion `.pain` (Eyebrow „Kennst du das?"): neuer `h2` ist der Einleitungssatz „Von außen läuft die Beziehung — innen fühlst du dich trotzdem nie ganz sicher."; der bisherige erläuternde Absatz wurde entfernt (der Kunde beschreibt die Sektion nur noch als „Einleitungssatz + drei Karten").
- Drei Karten ersetzt: „Nicht genug" / „Angespannt" / „Unsicher" mit den vom Kunden vorgegebenen Texten (wortgleich). Badge-Farben aus dem Original beibehalten, Emoji der ersten Karte auf 💭 (Grübeln/Selbstzweifel) statt 🔥 gesetzt, weil das alte 🔥 zum neuen Thema „Nicht genug" nicht mehr passt.
- Meta-Description, OG-Description, Footer-About und `og.svg` sprechen weiterhin vom Angebot („Ganzheitliches Mental-Coaching in München") — der Kunde hat diese Stellen nicht beauftragt, deshalb unangetastet (analog zum vorigen Änderungsblock).

- [x] umgesetzt

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
