# Leitlinien und Ziele des Übersetzungsprojekts

## Gesamtziel
Alle öffentlich sichtbaren BJC-Inhalte sollen auf Deutsch verfügbar sein, ohne Funktionalität oder Benutzererfahrung einzuschränken. Dabei orientieren wir uns an folgenden Grundsätzen:

- **Inhaltliche Gleichwertigkeit**: Deutsche Seiten transportieren denselben fachlichen Inhalt wie die englischen Vorlagen.
- **Technische Funktionsfähigkeit**: Alle interaktiven Komponenten (Navigation, Sprachumschaltung, Links, Assets) verhalten sich identisch.
- **Konsistenz**: Vokabular, Stil und Formatierung sind innerhalb der deutschen Versionen einheitlich.

## Arbeitspakete
1. **Übersetzen der HTML-/MD-Inhalte**  
   - Einheit 1 abgeschlossen (Laborseiten, optionale Projekte, Zusammenfassungen).  
   - Einheit 2: Aktuelle Kursstruktur (Labs & optionale Projekte) auf Deutsch; Legacy-/`old`-Material offen.  
   - Einheit 3: Labs 1–5, Investigations und optionale Projekte komplett auf Deutsch (Stand 2025-10-18); noch offen: Assessments/Legacy.  
   - Ausstehend: Einheiten 4–8, globale Seiten (Startseiten, Lehrer*innenmaterial, ggf. Indexe).

2. **Anpassung der Sprachumschaltung (JS/CSS)**  
   - `llab/script/curriculum.js` und `llab/script/library.js` wurden erweitert, um `de` als Sprache zu berücksichtigen.  
   - Weitere Komponenten, die sprachabhängige Pfade oder Parameter annehmen, müssen überprüft und ggf. ergänzt werden (z. B. zusätzliche Dropdown-Einträge, Fallbacks bei nicht vorhandenen `.de`-Ressourcen).

3. **Prüfung von Assets**  
   - Grafiken mit eingebettetem Text identifizieren und – falls sie für das Nutzererlebnis wesentlich sind – lokalisiert bereitstellen (z. B. über SVG/PSD-Quellen oder neue Varianten wie `…_de.png`).  
   - Alle sprachspezifischen Icons/Buttons (z. B. „Write in your journal“) auf deutsche Pendants prüfen.

4. **Qualitätssicherung**  
   - Spot-Checks der deutschen Seiten im Browser (Navigations-Flow, Sprachumschaltung, Links).  
   - Korrekturlesen durch Muttersprachler*innen, Fokus auf Lesbarkeit, Ton und einheitliche Terminologie.

## Qualitätskriterien
- **Technisch**: Keine 404-/Fetchausfälle, funktionierende Sprachumschaltung, korrekte Pfade (`*.de.html` und `*.de.topic`).  
- **Inhaltlich**: Fachliche Genauigkeit, vollständige Übertragung von Beispielen, Codeblocks, Tooltips, Kommentare.  
- **Sprachlich**: Konsistente Terminologie (siehe Glossar in `translation_process.md`), zielgruppengerechter Ton (Du-Form, klare Sprache).  
- **Barrierearmut**: Alt-Texte, Beschriftungen und ARIA-Attribute ggf. anpassen.  
- **Versionierung**: Übersetzungen transparent nachverfolgen (Commits, Diff-Historie, offene Todos).

## Vorgehen bei neuen Inhalten
1. Originaldatei analysieren (Struktur, Includes, Interaktivität).  
2. Übersetzung mit Blick auf bestehendes Glossar/Terminologie erarbeiten.  
3. Technische Referenzen prüfen (Links, Scripte, Parameter).  
4. Lokale Vorschau/Test im Browser.  
5. QA-Check (selbst + Peer Review).  
6. Dokumentation im Übersetzungslog/TODO aktualisieren.

## Zusammenarbeit
- **Kommunikation**: Fortschritt in `docs/ai_german/todo.md` halten; größere Änderungen über Issues/PRs kommunizieren.  
- **Rückmeldungen**: Feedback von Lehrkräften/Schüler*innen zeitnah übernehmen.  
- **Rollout**: Konkrete Meilensteine je Einheit definieren (z. B. „Einheit 2 fertig bis …“), danach Liveschaltung in Staging/Prod.

Diese Leitlinien dienen als Referenz für alle künftigen Arbeiten an der deutschen Lokalisierung des BJC-Materials.
