<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Rapperswil Jona: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-25 07:57 UTC, Rapperswil Jona: Systematische Sammlung (rapperswil-jona.tlex.ch): 41 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 6 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Rapperswil Jona: Systematische Sammlung (rapperswil-jona.tlex.ch)](https://rapperswil-jona.tlex.ch/) | `<act>/` | täglich | 2026-11-25 07:57 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 07:57](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261125t075709z) | lexwork-rapperswil-jona-city | 41 | 0 | 0 | 0 | 6 (0) | keine Änderung `verify-differ` | — |
| [2026-11-24 12:15](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261124t121549z) | lexwork-rapperswil-jona-city | 48 | 5 | 0 | 0 | 5 (0) | Änderungen gefunden `verify-differ` | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
