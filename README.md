# Schienbein Trainingsplan

Übungsplan gegen Schienbeinschmerzen innen bei nach innen knickenden Sprunggelenken. Die Seite läuft als statische Webseite auf GitHub Pages und ist für das Handy gebaut.

Live: https://huettenathor.github.io/schienenbein-app/

## Funktionen

* **Übersicht** mit allen 10 Übungen in 4 Blöcken, Steigerung über die Wochen und Hinweisen zum Laufen.
* **Geführtes Training** über „Training starten“ oder durch Tippen auf eine Übung. Jede Übung ist eine eigene Karte zum Wischen, mit Anleitung Schritt für Schritt, Sätzen zum Abhaken und Fortschrittsbalken.
* **Timer** bei Kurzfuß, Einbeinstand und Seitstütz. Sie geben Ton und Vibration beim Wechsel und haken die Seite am Ende automatisch ab. Der Ton lässt sich oben rechts ausschalten.
* **Bildschirm bleibt an**, solange das Training offen ist, sofern der Browser das unterstützt.
* **Wochenprotokoll** mit Häkchen und Schmerzwert. Nach dem Training lässt sich der Tag direkt eintragen. Die Seite merkt sich dann die aktuelle Woche und markiert die passende Steigerung.
* **Als App nutzen**: Im Browser „Zum Home Bildschirm“ wählen. Die Seite startet dann im Vollbild mit eigenem Icon.
* **PDF**: „Als PDF speichern“ öffnet den Druckdialog mit eigener Druckansicht.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Die komplette Seite mit Übungsdaten, Übersicht und geführtem Training |
| `manifest.webmanifest` | App Name, Farben und Icons für den Home Bildschirm |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App Icons |
| `.nojekyll` | Sorgt dafür, dass GitHub die Dateien unverändert ausliefert |

## Übungen ändern

Alle Übungen stehen in `index.html` im Abschnitt `Übungsdaten` als Liste. Jede Übung hat Name, Dosierung, Kurztext für die Übersicht, Schritte für die Karte, einen Hinweis, die Sätze zum Abhaken und optional einen Timer. Übersicht und Karten werden daraus automatisch erzeugt.

## GitHub Pages einschalten

1. Im Repo auf **Settings** gehen.
2. Links **Pages** wählen.
3. Bei **Source** die Option **Deploy from a branch** wählen.
4. Bei **Branch** `main` und `/ (root)` einstellen und **Save** klicken.
5. Nach ein bis zwei Minuten ist die Seite unter dem Live Link oben erreichbar.

## Hinweise

* Protokoll und Einstellungen werden nur im Browser des jeweiligen Geräts gespeichert. Am Handy und am Laptop stehen also getrennte Einträge.
* Der Plan ersetzt keine ärztliche oder physiotherapeutische Untersuchung.
