<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Birsfelden: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-27 05:50 UTC, Birsfelden: Systematische Sammlung (lex.birsfelden.ch): 22 Adressen gelesen; 2 hinzugefügt, 0 geändert, 0 entfernt; Änderungen gefunden; 12 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Birsfelden: Systematische Sammlung (lex.birsfelden.ch)](https://lex.birsfelden.ch/) | `<act>/` | täglich | 2026-11-27 05:50 UTC | Änderungen gefunden | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:50](checks/2026-11.md#ch-lexwork-birsfelden-city-20261127t055012z) | lexwork-birsfelden-city | 22 | 2 | 0 | 0 | 12 (0) | Änderungen gefunden `verify-differ` | — |
| [2026-11-26 05:48](checks/2026-11.md#ch-lexwork-birsfelden-city-20261126t054810z) | lexwork-birsfelden-city | 22 | 2 | 0 | 0 | 12 (0) | Änderungen gefunden `verify-differ` | — |
| [2026-11-25 06:00](checks/2026-11.md#ch-lexwork-birsfelden-city-20261125t060020z) | lexwork-birsfelden-city | 78 | 73 | 0 | 0 | 12 (0) | Änderungen gefunden `verify-differ` | [95](https://github.com/lexifina/switzerland-birsfelden-city-law/compare/62cb35482f67...405cf8b427b3) |
| [2026-11-24 14:33](checks/2026-11.md#ch-lexwork-birsfelden-city-20261124t143330z) | lexwork-birsfelden-city | 77 | 73 | 0 | 0 | 83 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 11:59](checks/2026-11.md#ch-lexwork-birsfelden-city-20261124t115947z) | lexwork-birsfelden-city | 112 | 83 | 0 | 0 | 83 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
