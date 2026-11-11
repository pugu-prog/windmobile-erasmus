# Windmobile Erasmus-Workshoptag 18.11.2026

Kontext für Claude Code (übernommen aus dem Claude-Artifact „Windmobile Workshoptag 18.11.“).

## Was das ist
Zweisprachige Planungsseite (DE/EN, Umschalter oben) für den Erasmus-Workshoptag am LTEtt, Mittwoch 18.11.2026.

- Live: https://pugu-prog.github.io/windmobile-erasmus/ (GitHub Pages baut aus Branch `gh-pages`: immer `git push origin main main:gh-pages`, `.nojekyll`)
- `index.html` – die ganze Seite in einer Datei (CSS + JS inline, Logos als eingebettete WebP-Data-URIs). Inhaltlich identisch mit dem Artifact.
- `media/` – Fotos (Gesichter herausgeschnitten) und Video der Harzinfusion aus dem Vorversuch, in den Fertigungs-Details
- `docs/` – Folien Energy market von Yves (PDF + PPTX, Stand 05.10.2026), von der Seite verlinkt

## Ablauf
- Zeitfenster 9:00–12:30 (Runden 9:00–10:40 / 10:50–12:30) und 13:30–16:30, je ca. 20 Schüler in zwei Gruppen à ~10; nach der Pause wird getauscht
- Station 1 – Fertigung Rotorblätter (Will Reiter, Pol Medernach), Raum 013 Werkstatt: Rotorblätter für ein Windrad aus zwei Fahrradfelgen, Sandwich-Bauweise mit Vakuuminfusion: zwei Carbonmatten mit Kern Lantor Soric SF (1200 mm, Easy Composites); Harz 300 g + 90 g Härter (Fast), 100:30; Runde 2 kürzer (75–80 min) mit vorgeschnittenen Matten
- Station 2 – Energy market (Yves), Raum 014: Workshop „European electricity markets“, 50 min, zwei Gruppenaufgaben (Merit-Order, Rollenspiel „Ein Sonntag, zwei Preise“)
- Station 3 – Energy tour (Guy Putz), Raum 014 → Schulhof: Timeline „20 Jahre Windmobile“, mobiles Windrad, C-Rotor
- Raum 014 ist nie doppelt belegt: dieselbe Gruppe hat erst Yves, dann Guy
- Vormittag fest ab 9:00 (früher Variante B); Missions-Präsentationen aus dem Gesamtplan (9:00–9:30) müssen verschoben werden

## Arbeitsweise
- Änderungen auf `main` und `gh-pages` pushen = live über GitHub Pages
- Seite ist für die Erasmus-Schüler freigegeben (seit 11.11.2026): keine internen Planungspunkte, Preise oder Bestellungen
- Jeder Text existiert zweimal (`.de` / `.en`); beide Sprachen immer zusammen ändern
- Seite muss auch am Handy funktionieren (Breakpoint 900 px) und hat Hell/Dunkel-Modus
