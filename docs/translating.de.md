# Übersetzung von BJC

Dieser Leitfaden beschreibt, wie BJC-Inhalte in andere Sprachen übertragen werden.

## Überblick

Jedes Objekt (Seite, Bild, XML-Datei) kann eine übersetzte Variante haben. Übersetzungen liegen immer direkt neben der englischen Datei. Der Dateiname bleibt gleich; die Sprachkennung wird ans Ende gesetzt (z. B. `hello.es.html` für Spanisch). Die aktuelle CSP-Version enthält bereits eine spanische WIP-Übersetzung.

Beispiel: Lab 1, Abschnitt „Building an App“. Die Inhalte liegen unter `cur/programming/1-introduction/1-building-an-app/`

```sh
$ ls -l cur/programming/1-introduction/1-building-an-app/
-rw-r--r--@ 1 Michael  staff   2897 Sep  7  2021 1-creating-a-snap-account.html
-rw-r--r--@ 1 Michael  staff  10699 Sep  7  2021 2-start-your-first-snap-app.html
-rw-r--r--@ 1 Michael  staff   6686 Sep  7  2021 3-loading-mobile-device.html
-rw-r--r--@ 1 Michael  staff   6424 Sep  7  2021 4-keeping-score.html
-rw-r--r--@ 1 Michael  staff   3116 Sep  7  2021 5-finish-your-first-snap-app.html
drwxr-xr-x@ 6 Michael  staff    192 Oct 13 15:44 old
```

Für jede Sprache behalten wir diese Verzeichnisstruktur bei – **Dateinamen werden nicht übersetzt**.

## Bilder übersetzen (TODO)

* Smart Pics verwenden
* Englische Grafiken aktualisieren
* Übersetzte Bilder exportieren
* Blockübersetzungen speichern und sowohl englische als auch spanische XMLs nachziehen
