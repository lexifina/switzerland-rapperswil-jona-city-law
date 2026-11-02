# Rapperswil-Jona (city): law history in git

The municipal law of the city of Rapperswil-Jona (Stadt Rapperswil-Jona, canton of St. Gallen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of St. Gallen is in [lexifina/switzerland-st-gallen-law](https://github.com/lexifina/switzerland-st-gallen-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

90 acts with 108 versions so far: the Gemeindeordnung (the city's charter) first, then the city's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 3 | oldest version available, then each consolidated version: 1 February 2024 to 1 January 2026 |
| `0-1-1/` | Vereinbarung Zweckverband «Kindes- und Erwachsenenschutz Region Zürichsee-Linth» (SRS 0.1-1) | 1 | as enacted, 27 September 2019 |
| `0-1-1-1/` | Geschäftsordnung der Kindes- und Erwachsenenschutzbehörde Linth (SRS 0.1-1.1) | 1 | as enacted, 1 July 2015 |
| `0-1-3-1/` | Geschäftsreglement der Zivilschutzkommission ZürichseeLinth (SRS 0.1-3.1) | 1 | as enacted, 1 April 2017 |
| `0-2-1/` | Statuten der Pensionskasse Stadt Rapperswil-Jona (SRS 0.2-1) | 1 | as enacted, 1 January 2021 |
| `1-3-1/` | Gebührentarif Einbürgerungsverfahren (SRS 1.3-1) | 1 | as enacted, 26 October 2020 |
| `1-6-1/` | Geschäftsreglement des Stadtrats (SRS 1.6-1) | 2 | as enacted, then each consolidated version: 1 June 2021 to 1 January 2025 |
| `1-6-2/` | Reglement betreffend die Übertragung von Befugnissen des Stadtrats (SRS 1.6-2) | 2 | as enacted, then each consolidated version: 4 January 2007 to 1 January 2025 |
| `1-6-3/` | Richtlinien zu Organisation, Aufgaben, Arbeitsweise des Stadtforums (SRS 1.6-3) | 2 | as enacted, then each consolidated version: 15 November 2012 to 1 June 2026 |
| `1-6-4/` | Reglement Kommission StadtLebensRaum 2040 (SRS 1.6-4) | 2 | as enacted, then each consolidated version: 1 October 2022 to 1 January 2025 |
| `1-7-1/` | Personalreglement (SRS 1.7-1) | 1 | one version (the oldest available), 1 January 2023 |
| `1-7-1-1/` | Weiterbildungsreglement (SRS 1.7-1.1) | 2 | as enacted, then each consolidated version: 1 January 2023 to 9 January 2023 |
| `1-7-1-2/` | Spesenreglement (SRS 1.7-1.2) | 1 | one version (the oldest available), 7 June 2022 |
| `1-7-1-3/` | Arbeitszeitreglement (SRS 1.7-1.3) | 1 | as enacted, 1 October 2023 |
| `1-7-2/` | Lehrpersonalreglement (SRS 1.7-2) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 August 2026 |
| `1-7-2-1/` | Spesenreglement für das Lehrpersonal (SRS 1.7-2.1) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 6 May 2024 |
| `2-1-1/` | Reglement über die Kosten der Nachführung der amtlichen Vermessung (SRS 2.1-1) | 1 | as enacted, 1 February 2020 |
| `4-1-3-reglement-feb/` | Reglement über die Beiträge der Stadt Rapperswil-Jona an die familienergänzende Kinderbetreuung (SRS 4.1-3) | 1 | as enacted, 1 August 2025 |
| `4-1-3-1/` | Ausführungsbestimmungen zum Reglement über die Beiträge der Stadt Rapperswil-Jona an die familienergänzende Kinderbetreuung - Städtische Beiträge Kindertagesstättenbetreuung (SRS 4.1-3.1) | 1 | as enacted, 1 August 2025 |
| `4-1-3-2/` | Ausführungsbestimmungen zum Reglement über die Beiträge der Stadt Rapperswil-Jona an die familienergänzende Kinderbetreuung - Städtische Tarife - Unterrichtsergänzende Betreuung (SRS 4.1-3.2) | 1 | as enacted, 1 August 2025 |
| `4-1-3-3/` | Ausführungsbestimmungen zum Reglement über die Beiträge der Stadt Rapperswil-Jona an die familienergänzende Kinderbetreuung – Städtische Beiträge Tagesfamilienbetreuung (SRS 4.1-3.3) | 2 | as enacted, then each consolidated version: 1 August 2025 to 1 December 2025 |
| `4-1-3-4-spielgruppen-und-vorkindergarten/` | Ausführungsbestimmungen zum Reglement über die Beiträge der Stadt Rapperswil-Jona an die familienergänzende Kinderbetreuung - Städtische Beiträge modulare Betreuung (SRS 4.1-3.4) | 1 | as enacted, 1 August 2026 |
| `4-2-1/` | Schulordnung (SRS 4.2-1) | 1 | as enacted, 1 May 2021 |
| `4-2-1-1/` | Schulleitungsreglement (SRS 4.2-1.1) | 1 | as enacted, 1 August 2021 |
| `4-2-1-2/` | Ausführungsbestimmungen zum Promotions- und Übertrittsreglement (SRS 4.2-1.2) | 1 | as enacted, 1 January 2007 |
| `4-2-1-3/` | Disziplinarordnung (SRS 4.2-1.3) | 1 | as enacted, 1 January 2007 |
| `4-2-1-4/` | Absenzen-, Urlaubs- und Dispensationsreglement für Schülerinnen und Schüler (SRS 4.2-1.4) | 1 | as enacted, 1 August 2012 |
| `4-2-2/` | Geschäftsreglement für den Schulrat (SRS 4.2-2) | 1 | as enacted, 1 August 2019 |
| `4-2-3/` | Richtlinien für besondere Unterrichtswochen, Sonderveranstaltungen, Schulreisen und Exkursionen (SRS 4.2-3) | 2 | as enacted, then each consolidated version: 1 August 2018 to 1 January 2025 |
| `4-2-4/` | Schulbesuchsvereinbarung (SRS 4.2-4) | 1 | as enacted, 27 June 2008 |
| `4-3-1/` | Bestimmungen zur Führung und Organisation der Musikschule Rapperswil-Jona (SRS 4.3-1) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 August 2026 |
| `5-1-1/` | Polizeireglement (SRS 5.1-1) | 2 | as enacted, then each consolidated version: 1 November 2017 to 1 April 2026 |
| `5-1-1-1/` | Vollzugsreglement über die Video-Überwachung auf öffentlichem Grund (SRS 5.1-1.1) | 1 | as enacted, 1 July 2009 |
| `5-1-1-2/` | Nutzung öffentlicher Raum für Aussenwirtschaften, Ausführungsbestimmungen (SRS 5.1-1.2) | 1 | as enacted, 28 August 2023 |
| `5-1-2/` | Immissionsschutzreglement (SRS 5.1-2) | 1 | as enacted, 1 July 2009 |
| `5-1-3/` | Reglement über Fundsachen (SRS 5.1-3) | 1 | as enacted, 1 February 2013 |
| `5-5-1/` | Feuerwehrreglement (SRS 5.5-1) | 1 | as enacted, 1 January 2022 |
| `5-5-1-1/` | Tarif und Entschädigungen zum Feuerwehrreglement (SRS 5.5-1.1) | 1 | one version (the oldest available), 1 July 2023 |
| `5-6-1/` | Reglement über den Seerettungsdienst (SRS 5.6-1) | 1 | as enacted, 1 March 1973 |
| `5-6-1-1/` | Tarif für den Seerettungsdienst (SRS 5.6-1.1) | 1 | as enacted, 1 January 2009 |
| `6-1-2/` | Reglement über die Reserve Werterhalt Finanzvermögen (SRS 6.1-2) | 1 | as enacted, 1 April 2019 |
| `6-1-3/` | Reglement über die Abgabe von stadteigenen Grundstücken (SRS 6.1-3) | 1 | as enacted, 1 January 2026 |
| `6-4-1/` | Gebührentarif für die Dienstleistungen des Einwohneramts (SRS 6.4-1) | 2 | as enacted, then each consolidated version: 1 January 2025 to 1 January 2027 |
| `6-6-1/` | Reglement für die Benützung des Stadtsaals KREUZ (SRS 6.6-1) | 1 | as enacted, 18 February 2008 |
| `6-6-1-1/` | Saalbenützungsordnung für den Stadtsaal KREUZ (SRS 6.6-1.1) | 1 | as enacted, 18 February 2008 |
| `6-6-2/` | Reglement über die Benützung von Schulräumen und ‑aussenanlagen durch die Öffentlichkeit, Vereine und andere Organisationen (SRS 6.6-2) | 1 | as enacted, 1 January 2010 |
| `6-6-2-1/` | Tarif für die Benützung der Schulräume und ‑aussenanlagen (SRS 6.6-2.1) | 1 | as enacted, 11 May 2009 |
| `6-6-3/` | Reglement über die Organisation und Benützung der Sporthalle Grünfeld (SRS 6.6-3) | 1 | as enacted, 1 June 2011 |
| `6-6-4/` | Reglement über die Benützung der Turnhallen (SRS 6.6-4) | 1 | as enacted, 1 January 2010 |
| `6-6-5/` | Reglement über die Organisation und Benützung der Aussen-Sportanlagen Grünfeld (SRS 6.6-5) | 1 | as enacted, 1 June 2011 |
| `6-6-6/` | Reglement über die Benützung der Eisanlagen Lido (SRS 6.6-6) | 1 | as enacted, 1 January 2011 |
| `6-6-7/` | Reglement über die Benützung der Freibäder (SRS 6.6-7) | 1 | as enacted, 1 July 2008 |
| `6-6-8/` | Reglement über die Nutzung der Lehrschwimmbäder (Hallenbäder) (SRS 6.6-8) | 2 | as enacted, then each consolidated version: 1 April 2010 to 1 August 2026 |
| `6-6-9/` | Reglement über die Organisation und Benützung des Wassersportzentrums für Kanu- und Rudersport (SRS 6.6-9) | 1 | as enacted, 1 November 2005 |
| `6-6-10/` | Reglement für die Benützung der Schiessanlage Grunau (SRS 6.6-10) | 1 | as enacted, 1 March 2011 |
| `7-1-1/` | Baureglement (SRS 7.1-1) | 1 | one version (the oldest available), 9 January 2013 |
| `7-1-1-1/` | Gebührentarif für das Bauwesen (SRS 7.1-1.1) | 1 | as enacted, 1 January 2014 |
| `7-1-2/` | Altstadtschutz-Verordnung (SRS 7.1-2) | 1 | one version (the oldest available), 21 August 2017 |
| `7-1-3/` | Schutzzonenreglement für die Grundwasserfassung «Hanfländer» (Wasserversorgung der Stadt Rapperswil) (SRS 7.1-3) | 1 | one version (the oldest available), 14 April 2009 |
| `7-1-4/` | Schutzzonenreglement für die Grundwasserfassung «Wagen» (Eigentum der Wasserversorgung Rüti ZH) (SRS 7.1-4) | 1 | as enacted, 4 May 2000 |
| `7-1-5/` | Schutzzonenreglement für die Grundwasserfassung «Hessenhof» (Versuchsbrunnen) (SRS 7.1-5) | 1 | as enacted, 29 May 1997 |
| `7-1-6/` | Schutzzonenreglement für die Grundwasserfassung «Busskirch» (Eigentum der Wasserversorgung Rapperswil) (SRS 7.1-6) | 1 | one version (the oldest available), 14 April 2009 |
| `7-1-7/` | Schutzzonenreglement für die Grundwasserfassung «Tägernau» (SRS 7.1-7) | 1 | as enacted, 18 July 2012 |
| `7-1-8/` | Schutzzonenreglement für die Grundwasserfassung «Joneren» (Eigentum der Wasserversorgung Eschenbach) (SRS 7.1-8) | 1 | as enacted, 14 May 1997 |
| `7-1-9/` | Schutzzonenreglement für die Grundwasserfassung «Grünfeld» (Eigentum der Wasserversorgung Jona) (SRS 7.1-9) | 1 | one version (the oldest available), 14 April 2009 |
| `7-1-10/` | Parkplatzbedarfs-Reglement (SRS 7.1-10) | 1 | as enacted, 1 June 2010 |
| `7-3-1/` | Natur- und Denkmalschutzverordnung (SRS 7.3-1) | 1 | as enacted, 16 July 2010 |
| `7-3-2/` | Reglement über Luftreinhaltemassnahmen bei Feuerungen (SRS 7.3-2) | 2 | as enacted, then each consolidated version: 16 February 2009 to 1 January 2026 |
| `7-3-2-1/` | Gebührentarif für Luftreinhaltemassnahmen bei Öl- und Gasfeuerungen sowie für Holzfeuerungskontrollen (SRS 7.3-2.1) | 2 | as enacted, then each consolidated version: 16 February 2009 to 1 January 2026 |
| `7-3-4/` | Reglement Förderprogramm Ersatz von fossilen Heizungen (SRS 7.3-4) | 1 | as enacted, 1 January 2024 |
| `7-3-4-1/` | Vollzugsvorschriften Förderprogramm Ersatz von fossilen Heizungen (SRS 7.3-4.1) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 September 2026 |
| `7-4-3-1/` | Reglement über die Wasserversorgung (SRS 7.4.3-1) | 1 | as enacted, 1 January 2007 |
| `7-4-3-1-1/` | Beiträge und Gebühren der Wasserversorgung (SRS 7.4.3-1.1) | 1 | as enacted, 1 January 2007 |
| `7-4-3-2/` | Abwasserreglement (SRS 7.4.3-2) | 1 | one version (the oldest available), 1 December 2011 |
| `7-4-4-1/` | Reglement über die Abfallentsorgung (SRS 7.4.4-1) | 1 | as enacted, 12 August 2009 |
| `7-4-4-1-1/` | Gebührentarif zum Abfallreglement (SRS 7.4.4-1.1) | 1 | as enacted, 28 September 2009 |
| `7-7-1/` | Parkierungs- und Parkgebühren-Reglement (SRS 7.7-1) | 1 | as enacted, 13 August 2009 |
| `7-7-2-hafenordnung/` | Verordnung über die Hafenanlagen (SRS 7.7-2) | 1 | as enacted, 10 December 2009 |
| `7-7-3-grabenordnung/` | Ausführungsbestimmungen bei Belagsaufbrüchen und Aufgrabungen auf dem Gemeindegebiet (SRS 7.7-3) | 1 | as enacted, 16 February 2026 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 21 October 2010 |
| `8-2-1-1/` | Gebührentarif betreffend die Übernahme von Todesfallkosten (SRS 8.2-1.1) | 1 | as enacted, 9 May 2022 |
| `8-7-1/` | Reglement Jugendrat (SRS 8.7-1) | 1 | as enacted, 1 January 2024 |
| `8-7-2/` | Reglement über die stationären Einrichtungen im Altersbereich (SRS 8.7-2) | 1 | as enacted, 1 June 2014 |
| `8-7-3/` | Reglement über den Fonds zur Finanzierung der Rückstellungskosten Zeitvorsorgemodell St. Gallen (SRS 8.7-3) | 1 | as enacted, 9 May 2021 |
| `8-8-1/` | Reglement zur Förderung von preisgünstigem Wohnraum (SRS 8.8-1) | 1 | as enacted, 1 May 2023 |
| `9-4-1/` | Kurtaxenreglement (SRS 9.4-1) | 1 | as enacted, 1 January 2010 |
| `9-4-1-1/` | Ausführungsbestimmungen zum Kurtaxenreglement (SRS 9.4-1.1) | 1 | as enacted, 1 January 2010 |
| `9-5-1/` | Reglement über Ruhetag und Ladenöffnung (SRS 9.5-1) | 1 | as enacted, 1 December 2009 |
| `9-5-2/` | Gastwirtschaftsreglement (SRS 9.5-2) | 1 | one version (the oldest available), 5 December 2023 |
| `9-5-2-1/` | Gebührentarif zum Gastwirtschaftsreglement (SRS 9.5-2.1) | 1 | as enacted, 1 July 2009 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://rapperswil-jona.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@rapperswil-jona.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
