# Übersetzungsprozess und Terminologie-Leitfaden

Dieses Dokument fasst den bisherigen Übersetzungsprozess zusammen und dient als Nachschlagewerk, um zukünftige Lokalisierungen konsistent zu halten.

## Prozessüberblick
1. **Analyse**  
   - Originaldatei (HTML/MD) strukturieren: Navigation, interaktive Bereiche, Snippets, ggf. eingebettete Skripte.  
   - Prüfen, ob bereits eine `.es`-Version existiert; diese kann als Referenz dienen, wenn Begriffe bereits lokalisiert wurden.
2. **Übersetzung**  
   - Inhalte in der Reihenfolge des Dokuments übertragen.  
   - Code-Blöcke, Variablennamen, Snap!-Reporter unverändert lassen, sofern es sich um konkrete Blocknamen handelt.  
   - Inline-Kommentare und Alt-Texte anpassen.
3. **Technik-Check**  
   - Links/Pfade auf `.de.html`/`.de.topic` umstellen.  
   - Sprachabhängige Parameter (z. B. `lang`-Attribute, `pageLang`, `llab.supportedLanguages`) prüfen.  
   - Dropdown-Einträge für die Sprachwahl ergänzen.
4. **Review**  
   - Selbstcheck im Browser (Layout, Interaktion).  
   - Optional Peer Review (Lesbarkeit, Terminologie).  
5. **Dokumentation**  
   - Status in `docs/ai_german/todo.md` aktualisieren.  
   - Neue oder geänderte Terminologie unten ergänzen.

## Terminologie & Stil
| Englischer Begriff | Deutsche Übersetzung | Begründung / Hinweise |
|--------------------|---------------------|------------------------|
| sprite             | Sprite              | Technischer Begriff aus Snap!, nicht übersetzt. |
| costume            | Kostüm              | In Snap! etabliert, in Tutorials üblich. |
| stage              | Bühne               | Snap!-Oberfläche nennt den Bereich „Stage“. |
| script             | Skript              | Entwicklerterminologie, geläufig im Deutschen. |
| block (Snap!)      | Block               | Wird in Snap! selbst verwendet; keine Übersetzung nötig. |
| reporter block     | Reporter-Block      | Zusammensetzung, da „Reporter“ offizieller Snap!-Begriff ist. |
| command block      | Kommando-Block      | Wörtliche Übersetzung, beschreibt Funktion. |
| forever loop       | `forever`-Schleife / Endlosschleife | Je nach Kontext; wenn Blockname ausdrücklich erwähnt, im Code belassen. |
| repeat until       | `repeat until`-Schleife | Blockname bleibt Englisch, Funktionsbeschreibung deutsch. |
| list               | Liste               | Standardterminus. |
| string             | Zeichenkette        | Informatik-Standard. |
| concatenation      | Verkettung          | Begriffsgebrauch aus der Programmierdidaktik. |
| debugging          | Debugging           | Übernommen, häufig verwendet; ggf. kurz erläutern. |
| find first         | find first          | Snap!-Blockname bleibt Englisch; im Fließtext kurz erklären („find first sucht das erste passende Listenelement“). |
| personally identifiable information (PII) | personenbezogene Daten (PII) | Deutsche Entsprechung plus Abkürzung für Wiedererkennung. |
| privacy            | Privatsphäre        | Allgemeingebräuchlich. |
| vocabulary         | Vokabular           | Standardbeschriftung für Vokabular-Kästen und Überschriften. |
| learner address („you“) | Du-Form        | Einheitlicher Stil: direkte Anrede („du/ihr“). |

### Snap!-spezifische Begriffe
- Blocknamen, Menübezeichnungen, Dropdown-Einträge bleiben in der UI-Sprache (Englisch), da sie 1:1 in Snap! erscheinen. Beispiel: `when green flag clicked`, `pen down`. Im Text kann eine deutsche Umschreibung folgen („Klicke auf den Block `pen down` (Stift absetzen)“).
- Reporter-/Kommando-Namen, die selbst erstellt wurden, können deutsch benannt werden, wenn die Lernenden den Block anlegen (z. B. `draw square` → `zeichne Quadrat`). Bei Automatisierung/Standardblöcken im Code lieber Original lassen.
- Höhere-Ordnungs-Funktionen wie `map`, `keep`, `combine`, `find first` behalten ihre englischen Namen; ergänze kurze Funktionsbeschreibungen im Text.

### Mehrdeutige Begriffe & Entscheidungen
- **Leader / Follower** im Labor „Follow the Leader“ wurden als „Leader“ und „Follower“ belassen, da sie im UI als Sprite-Namen vorkommen und so den Codebeispielen entsprechen. Optional wird im Fließtext erklärt, was sie bedeuten („Der Sprite `Leader` (Anführer) ...“).
- **Chunk „Take It Further/Take It Teased/If There Is Time“**: Statt wörtlicher Übernahme wurde einheitlich „Take it Further“ → „Take It Further“ (hinweisende Box), „If There Is Time“ → „Wenn noch Zeit ist“, „Take It Teased“ → „Teaser“; Box-Titel in `llab.TRANSLATIONS` ergänzen.
- **„Stage“/„Bühne“**: In Snap! UI englisch, im Fließtext „Bühne“ – alt-Texte ebenfalls in Deutsch (z. B. „Sprite folgt deiner Maus auf der Bühne“).
- **„Repeat until“**: Blockname beibehalten, Beschreibung „Wiederhole solange, bis ...“. So erkennen Lernende die UI sofort wieder.
- **„Mouse pointer“** → „Mauszeiger“; in Blockauswahl bleibt der englische Eintrag bestehen.

## Nicht übersetzte Inhalte & Gründe
- Code-Listings, Snap!-Blocknamen, Variablennamen: identisch mit englischem Projekt, damit Lernende die Beispiele direkt ausführen können.
- Dateien aus `prog/` (Snap!-XML-Projekte): enthalten UI-Strings; Übersetzung würde Snap!-Blöcke verändern. Stattdessen Anleitungen/Kommentare übersetzen.
- Spezifische TODO-Kommentare (`// TODO`) oder Entwicklerhinweise: bleiben unverändert, sofern sie sich auf Code beziehen.

## Empfehlungen für künftige Übersetzungen
1. **Vor der Übersetzung** das Glossar prüfen und bei Bedarf erweitern.  
2. **Währenddessen**: Bei unklaren Begriffen Staging-Server konsultieren oder Snap!-UI auf Deutsch öffnen (falls verfügbar), um offizielle Terminologie abzugleichen.  
3. **Nach der Übersetzung**: Terminologieänderungen in diesem Dokument ergänzen; offene Fragen in Issues/TODO festhalten.

Dieses Dokument wird laufend aktualisiert, sobald neue Begriffe hinzukommen oder Übersetzungsentscheidungen angepasst werden.
