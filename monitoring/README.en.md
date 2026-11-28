<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Birsfelden only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:48 UTC, Birsfelden: systematic collection (lex.birsfelden.ch): 22 addresses read; 2 added, 0 changed, 0 removed; changes found; 12 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Birsfelden: systematic collection (lex.birsfelden.ch)](https://lex.birsfelden.ch/) | `<act>/` | daily | 2026-11-28 05:48 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:47](checks/2026-11.md#ch-lexwork-birsfelden-city-20261128t054747z) | lexwork-birsfelden-city | 22 | 2 | 0 | 0 | 12 (0) | changes found `verify-differ` | — |
| [2026-11-27 05:50](checks/2026-11.md#ch-lexwork-birsfelden-city-20261127t055012z) | lexwork-birsfelden-city | 22 | 2 | 0 | 0 | 12 (0) | changes found `verify-differ` | — |
| [2026-11-26 05:48](checks/2026-11.md#ch-lexwork-birsfelden-city-20261126t054810z) | lexwork-birsfelden-city | 22 | 2 | 0 | 0 | 12 (0) | changes found `verify-differ` | — |
| [2026-11-25 06:00](checks/2026-11.md#ch-lexwork-birsfelden-city-20261125t060020z) | lexwork-birsfelden-city | 78 | 73 | 0 | 0 | 12 (0) | changes found `verify-differ` | [95](https://github.com/lexifina/switzerland-birsfelden-city-law/compare/62cb35482f67...405cf8b427b3) |
| [2026-11-24 14:33](checks/2026-11.md#ch-lexwork-birsfelden-city-20261124t143330z) | lexwork-birsfelden-city | 77 | 73 | 0 | 0 | 83 (0) | the check failed | — |
| [2026-11-24 11:59](checks/2026-11.md#ch-lexwork-birsfelden-city-20261124t115947z) | lexwork-birsfelden-city | 112 | 83 | 0 | 0 | 83 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
