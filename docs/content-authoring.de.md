# Autorenschaft

> **TODO:** Diese Seite braucht ein größeres Update – die bisherigen Hinweise gelten trotzdem.

## [Übersetzen](./translating.de.md)

## Struktur

* Course
    * Topic
        * Curriculum Page

## Schreibstil
Ein paar Tipps, um Ton und Stil konsistent zu halten:

* Vermeide Verweise auf Berkeley oder CS10.
* Schreibe in der Du-/Ihr-Form.
* Absätze kurz, aber nicht stakkato.
* _Empfehlungen zur Seitenlänge folgen noch._
* Stil: zwischen umgangssprachlich und formell.
* Verständlich für Oberstufen-Lernende schreiben.
* „Snap!“ immer als `<span class="snap">snap</span>` setzen.
* Programmierkonzepte klar von Snap-Begriffen trennen.
* _Kontraktionen vermeiden („don't“, „can't“ …)._
* Neue Fachbegriffe erklären.
* Mehr folgt. :-)

Trotz des Rohzustands gilt: Rechtschreibung, Grammatik und Zeichen­setzung müssen stimmen – „typo talk“ wartet auf Überarbeitung.

## Features
Es gibt diverse CSS-/HTML-Bausteine für Labs (diese Seite wird bald ergänzt):

* Inline-Bilder
* Quizzes
* Tipps/Hinweisboxen
* Spezielle Überschriften
* Definitionen

## Content Management
Die Ordnerstruktur wirkt teils eigen – bitte halten:

1. Beschreibende Dateinamen wählen (lange Namen sind okay).
2. Kleinbuchstaben bevorzugen (das `HOFs`-Verzeichnis ist schlechtes Vorbild).
3. TBD

Wichtige Ordner:

* `course` – Kurse
* `cur` – **Lab-Inhalte (HTML/MD)**
* `glossary` – ungenutzt
* `img` – **alle Bilder**
  * `img/blocks` – **Einzelne Block-Screenshots**
* `prog` – **Snap/BYOB-Dateien für Labs**
* `topic` – Topic-Metadaten

Für `cur`, `img`, `prog` gilt eine thematische Struktur (nicht strikt, aber Orientierung):

_Nicht nach Lab-Nummern organisieren!_

* `programming/`
   * `abstraction`
   * `algorithms`
   * `build-a-block`
   * `concurrency`
   * `conditionals`
   * `data`
   * `distributed`
   * `functions`
   * `hash-tables`
   * `HOFs`
   * `internet`
   * `intro`
   * `lists`
   * `loops`
   * `projects`
   * `random`
   * `recursion`
   * `sequential-v-parallel`
   * `simulation`
   * `snap`
   * `sorting`
   * `strings`
   * `variables`
* `social-context/`
   * `apps`
   * `areas`
   * `concerns`
   * `future`
   * `history`
   * `misc`
