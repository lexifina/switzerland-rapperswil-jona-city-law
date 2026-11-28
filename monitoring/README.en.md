<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Rapperswil Jona only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:13 UTC, Rapperswil Jona: systematic collection (rapperswil-jona.tlex.ch): 39 addresses read; 0 added, 0 changed, 0 removed; no change; 5 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Rapperswil Jona: systematic collection (rapperswil-jona.tlex.ch)](https://rapperswil-jona.tlex.ch/) | `<act>/` | daily | 2026-11-28 08:13 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:12](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261128t081227z) | lexwork-rapperswil-jona-city | 39 | 0 | 0 | 0 | 5 (0) | no change `verify-differ` | — |
| [2026-11-28 07:07](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261128t070729z) | lexwork-rapperswil-jona-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:38](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261128t063811z) | lexwork-rapperswil-jona-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 06:49](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261127t064941z) | lexwork-rapperswil-jona-city | 37 | 0 | 0 | 0 | 6 (0) | no change `verify-differ` | — |
| [2026-11-26 06:51](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261126t065124z) | lexwork-rapperswil-jona-city | 44 | 0 | 0 | 0 | 5 (0) | no change `verify-differ` | — |
| [2026-11-25 07:57](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261125t075709z) | lexwork-rapperswil-jona-city | 41 | 0 | 0 | 0 | 6 (0) | no change `verify-differ` | — |
| [2026-11-24 12:15](checks/2026-11.md#ch-lexwork-rapperswil-jona-city-20261124t121549z) | lexwork-rapperswil-jona-city | 48 | 5 | 0 | 0 | 5 (0) | changes found `verify-differ` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
