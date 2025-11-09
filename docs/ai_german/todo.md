# TODO – Deutsche Lokalisierung

## Offene Übersetzungen
- [x] Einheit 1 (Introduction) – Kern- und optionale Seiten in `.de.html`. Review offen.  
- [ ] Einheit 2 (Conditionals & Abstraction)  
  - [x] Labs & optionale Projekte in aktueller Struktur.  
  - [ ] Legacy-/`old`-Material bleibt unverändert; keine Lokalisierung oder Archivierung geplant.  
  - [ ] Doppelte Selbsttestversion klären: `cur/programming/2-complexity/2-data-structures-art/assessment-data2.html` vs. `cur/programming/summaries/assessment-data2.{html,de.html}` → Entscheidung zu Weiterleitung/Archiv treffen.  
- [ ] Einheit 3 (Data Structures)  
  - [x] Labor 1 (Abstraction) Seiten 1–6.  
  - [x] Labor 2 (Contact List) Seiten 1–5.  
  - [x] Labor 3 (Tic-Tac-Toe) Seiten 1–3 – neu übersetzt (2025-10-18).  
  - [x] 4-Robots & AI (4 Seiten) – abgeschlossen (2025-10-18).  
  - [x] 5-Work (3 Seiten) – abgeschlossen (2025-10-18).  
  - [x] Investigations (5 Seiten) – abgeschlossen (2025-10-18).  
  - [x] Optionale Projekte (4 Seiten) – abgeschlossen (2025-10-18).  
  - [ ] Assessments & Legacy (`old/`, `unused-*`) → Relevanz klären.  
- [ ] Einheit 4 (Internet & Privacy)  
  - [x] Labor 1 (Computer Networks) Seiten 1–4 – abgeschlossen (2025-10-24).  
  - [x] Labor 2 (Cybersecurity) Seiten 1–6 – abgeschlossen (2025-10-24).  
  - [x] Labor 3 (Community & Online Interactions) – `.de`-Seiten bereinigt (TODO-Boxen entfernt, Inhalte ergänzt, Video-/Linklisten geprüft).  
- [ ] Einheit 5 (Algorithms & Simulations)  
  - [x] Labor 1 (Searching Lists) Seiten 1–8 – abgeschlossen (2025-10-31).  
  - [x] Labor 2 (Simulations) Seiten 1–2 – abgeschlossen (2025-10-31).  
  - [ ] Labor 3 (Turning Data into Information)  
    - [x] Seiten 1–6 – abgeschlossen (2025-10-31).  
  - [ ] Labor 4 (Unsolvable & Undecidable Problems)  
    - [x] Seiten 1–2 – abgeschlossen (2025-10-31).  
  - [ ] Labor 5 (Computing in War)  
    - [x] Seiten 1–3 – abgeschlossen (2025-10-31).  
  - [ ] Labor 6 (Tic-Tac-Toe with Computer Player)  
    - [x] Seiten 1–4 – abgeschlossen (2025-10-31).  
  - [ ] Optionales Labor (Other Programming Languages)  
    - [x] Seiten 1–3 – abgeschlossen (2025-10-31).  
  - [ ] Optionales Thema „Mutation“  
    - [x] Seiten 1–3 – abgeschlossen (2025-10-31).  
  - [ ] Weitere Labs/Projekte.  
- [ ] Einheit 6 (How Computers Work) – komplette Übersetzung.  
  - [ ] Labor 1 (Abstraction)  
    - [x] Seite 1 („Abstraktion im Inneren des Computers“) – neu übersetzt (2025-11-01).  
    - [x] Seiten 2–10 („Software-Domäne: Anwendungen/Programmiersprachen/Bibliotheken/Betriebssysteme“, „Digitale Domäne: Architektur/Komponenten/ICs/Logikgatter“, „Analoge Domäne: Transistoren“) – neu übersetzt (2025-11-01).  
  - [ ] Labor 2 (History & Impact)  
    - [x] Seite 1 („A Brief History of Computers“) – neu übersetzt (2025-11-01).  
    - [x] Seite 2 („Mooresches Gesetz“) – neu übersetzt (2025-11-01).  
  - [ ] Optionale Projekte  
    - [x] Binäraddierer (Seiten „Binary Addition with Logic Gates“, „Building a Binary Adder“) – neu übersetzt (2025-11-01).  
    - [x] Weather-App-Projekt („Weather App Project“) – neu übersetzt (2025-11-01).  
- [ ] Einheit 7 (Recursion) – komplette Übersetzung.  
  - [ ] Labor 1 (Trees)  
    - [x] Seiten 1–5 („Recursive Tree“, „The Base Case“, „Tree Inputs“, „Tree Variations“, „Vary Your Tree“) – neu übersetzt (2025-11-01).  
  - [ ] Labor 2 (Projects)  
    - [x] Seiten 1–4 („Triangle Fractal“, „Koch Snowflake“, „Lévy C-Curve“, „Recursive Mondrian“) – neu übersetzt (2025-11-01).  
- [ ] Einheit 8 (Recursive Reporters) – komplette Übersetzung.  
- [ ] Lehrkräfte-/Kursstartseiten (z. B. `course/*.html`, `index*.html`) lokalisieren.  
- [ ] Globale Ressourcen (FAQ, Docs, evtl. `docs/*`) prüfen.

## Technische Anpassungen
- [ ] Sprachumschalter weiter testen: Themen ohne `.de`-Datei liefern Fallback → Logging/Fehlermeldung verbessern.  
- [ ] Navigation/Dropdowns (z. B. Startseiten, `topic.html`) auf fehlende „Deutsch“-Option prüfen.  
- [ ] Eventuelle `pageLang`-Referenzen / SEO-Meta-Tags ergänzen.

## Assets & Styling
- [ ] Grafiken mit Text ermitteln und ‑ falls nötig ‑ deutsche Varianten erstellen (Icons in `img/icons`, Banner).  
- [ ] Alt-Texte der importierten Bilder nachziehen (Units 2–8, sobald übersetzt).  
- [ ] Box-Titel/Labels in `llab.TRANSLATIONS` erweitern (z. B. „Take It Further“, „If There Is Time“, Toolbox-Hinweise).

## Qualitätssicherung
- [ ] Browser-Check (Layout, Sprachumschaltung, Links) für bereits übersetzte Seiten.  
- [ ] Glossar in `translation_process.md` regelmäßig aktualisieren (neue Begriffe, Entscheidungen).  
- [ ] Peer Review / Lektorat der fertigen Einheiten einplanen.

## Dokumentation & Prozesse
- [ ] Diese TODO-Liste nach jeder abgeschlossenen Einheit aktualisieren.  
- [ ] Feedback aus Tests sammeln und im Guidelines-Dokument ergänzen.  
- [ ] Rollout-Plan festlegen (Reihenfolge, Staging → Produktion).

_Stand: 2025-10-31_
