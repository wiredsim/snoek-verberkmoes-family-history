# Duplicate Person Audit — 01-People

**Date:** 2026-06-05
**Scope:** All 829 person pages under `01-People/` (Coffin, Samargia, Snoek, VerBerkmoes, Related).
**Method:** Extracted the name + birth/death/parent/child summary from every page and cross-referenced by name, birth date, and family relationships.

## Why the duplicates exist

Every page carries the footer *"Auto-created from chronological event(s) in History of the
Coffin, Samargia, Snoek, VerBerkmoes Families by Ruth Taber."* The vault was **machine-generated
from a source document, one note per chronological event**. The same individual therefore spawned
multiple notes whenever they appeared in more than one event, and OCR/transcription produced
spelling variants. Four recurring patterns:

1. **Maiden ↔ married name split** — a woman's *birth* event became one note (maiden name + year)
   and her *marriage/death* event became a second note (married surname). Same person.
2. **Spelling / OCR variants** — the same name transcribed two or more ways
   (e.g. *Meinel / Meinal / Meil*, *Ter Archer / TerArchter*, *Jobin / Tobin*).
3. **Event fragments** — a marriage or city-directory line became a standalone "person"
   (e.g. *George McNamara G H, MI*) that duplicates a real person note.
4. **Non-person artifacts** — places, cemeteries, and historical headlines extracted as people.

> ⚠️ **Note on fixing:** this repository contains only the **built HTML** output (no markdown
> source). Editing/deleting files here will be overwritten on the next site rebuild. Apply the
> merges below in the **source vault / generator**, then rebuild. This document is the map.

Legend: **KEEP** = suggested surviving note (usually the one with birth data). **→ merge** = fold
into the KEEP note. Confidence noted per cluster.

---

## A. Maiden-name ↔ married-name splits (same individual) — HIGH confidence

| Person | Notes to merge | Keep |
|---|---|---|
| Aaltje (Alice) Bosman | `Related/Aaltje-Alice-Bosman-1865` (b.) + `VerBerkmoes/Aaltje-Alice-Bosman-VerBerkmoes` (d.1892, wife of Kryn) | birth note |
| Alecia Marie Crain | `Related/Alecia-Marie-Crain-1982` (b.) + `Related/Alecia-Marie-Crain-Devereau` (div.2019) | birth note |
| Anna P Unsinn | `Related/Anna-P-Unsinn-1876` (b.) + `Related/Anna-P-Unsinn-Speerschneider` (m.1920) | birth note |
| Anne Delores Rozzo | `Related/Anne-Delores-Rozzo-1928` (b. Ohio) + `Related/Anne-Delores-Rozzo-Sayers` (d.1969 Ashtabula) | birth note |
| Della (Adele) VerBerkmoes | `VerBerkmoes/Della-Adele-VerBerkmoes-1884` (b.) + `VerBerkmoes/Della-Adele-VerBerkmoes-Rinn` (d.1905) | birth note |
| Dionis Stevens | `Related/Dionis-Stevens-1610` (b.) + `Coffin/Dionis-Stevens-Coffin` (d.1676) | one note (wife of Tristram Coffin) |
| Elizabeth Mae Snoek | `Snoek/Elizabeth-Mae-Snoek-1904` (b.) + `Snoek/Elizabeth-Mae-Snoek-Webster` (d.1931) | birth note |
| Emma Coffin (Claflin) | `Coffin/Emma-Coffin-1867` (b.) + `Coffin/Emma-Coffin-Claflin` (d.1940) + `Related/Emma-Coffi-n` (m.1887) | birth note (3 notes → 1) |
| Harriette Smith | `Related/Harriette-Smith` (m.1837) + `Coffin/Harriette-Smith-Coffin` (d.1869) | one note |
| Henrickie Pruim | `Related/Henrickie-Pruim-1876` (b.) + `VerBerkmoes/Henrickie-Pruim-VerBerkmoes` (d.1951) | birth note |
| Jeanette Louise Leonard | `Related/Jeanette-Louise-Leonard-1879` (b.) + `Related/Jeanette-Louise-Leonard-Roper` (d.1937) | birth note |
| Maria Louisa Snavely | `Related/Maria-Louisa-Snavely-1844` (b.) + `Coffin/Maria-Louise-Snavely-Coffin` (d.1904) | birth note |
| Margaret Wood Sayers | `Related/Margaret-Wood-Sayers-1902` (b.) + `VerBerkmoes/Margaret-Wood-Sayers-VerBerkmoes` (d.1967) | birth note |
| Martha Ann Coffin | `Coffin/Martha-Ann-Coffin-1840` (b.) + `Coffin/Martha-Ann-Coffin-Heidelberg` (d.1918) | birth note |
| Opal Marie Cartwright | `Related/Opal-Marie-Cartwright-1908` (b. Marion IN) + `VerBerkmoes/Opal-Marie-Cartwright-VerBerkmoes` (d.1939 Marion IN) | birth note |
| Phoebe Coffin | `Coffin/Phoebe-Coffin-1847` (b., m. Harder) + `Coffin/Phoebe-Coffin-Harder` (later event) | birth note — *child links on the Harder note look mis-attributed; verify* |
| Rose Ann Bryant | `Related/Rose-Ann-Bryant-1939` (b.) + `Snoek/Rose-Ann-Bryant-Snoek` (d.2012) | birth note |
| Sarah Atkinson | `Related/Sarah-Atkison-1665` (b.) + `Related/Sarah-Atkinson` (m.1685) + `Coffin/Sarah-Atkinson-Coffin` (d.1724) | birth note (3 → 1; note *Atkison/Atkinson* spelling) |
| Sarah Janette Leendertsd Faas | `Related/Sarah-Janette-Leendertsd-Faas-1851` (b.) + `VerBerkmoes/Sarah-Jenette-Leendertsd-Faas-VerBerkmoes` (d.) | birth note (*Janette/Jenette*) |
| Susan A VerBerkmoes | `VerBerkmoes/Susan-A-VerBerkmoes-1881` (b.) + `VerBerkmoes/Susan-A-VerBerkmoes-Abbott-Rutledge` (d.) | birth note |
| Trinjtje B Eibema | `Related/Trinjtje-B-Eibema-1825` (b.) + `Snoek/Trinjtje-B-Eibema-Snoek` (d.1879) | birth note |
| Viola Lou VerBerkmoes | `VerBerkmoes/Viola-Lou-VerBerkmoes-1908` (b.) + `VerBerkmoes/Viola-Lou-VerBerkmoes-Flemming` (d.1977) | birth note |
| Elizabeth VerBerkmoes (Deephouse / McNamara) | `VerBerkmoes/Elizabeth-VerBerkmoes-1890` (b.) + `VerBerkmoes/Elizabeth-VerBerkmoes-Deephouse` (m.1921) + `VerBerkmoes/Elizabeth-VerBerkmoes-Deephouse-McNamara-5m-15dy` (d.) | birth note (3 → 1) |

## B. OCR / spelling-variant duplicates (same individual) — HIGH confidence

| Person | Notes to merge | Note |
|---|---|---|
| Adam Michael Devereaux | `Related/Adam-Michael-Devereau-1981` + `Related/Adam-Michael-Devereaux` | Devereau / Devereaux |
| Arron Lee Patten | `Related/Arron-Lee-Patten` + `Related/Arron-Lee-Patton` | Patten / Patton (his son `…-Patten-Jr-1986` is a **separate** person — keep) |
| Barbara Van Houten | `Related/Barbara-Van-Houten` + `Related/Barbara-Van-Houton` | both = dau. of Cornelius Jay Van Houten & Ruth Kooi |
| Beverly Van Houten | `Related/Beverly-Van-Houten` + `Related/Beverly-Van-Houton` | same dau.; *Betty-Van-Houton is a different sister — keep* |
| Cornelis Clarence (father) | `Related/Cornelis-Clamce` + `Related/Cornelis-Clarence` | *Clamce* = OCR of *Clarence* |
| Donald Howard TerArchter | `Related/Donald-Howard-Ter-Acher-1916` + `Related/Donald-Howard-TerArchter-1916` | both b. Jul 15 1916 |
| Dorothy "Jeanne" Rezny | `Related/Dorothy-Jeanne-Rezny-1931` + `Related/Dorthy-Jeanne-Rezny` | Dorothy / Dorthy |
| Emma Ida Meinel (Wheat) | `Related/Emma-Ida-Meil` + `Related/Emma-Ida-Meinal` + `Related/Emma-Ida-Meinel-1878` + `Related/Emma-Ida-Meinel-Wheat` | **4 notes → 1** (Meil/Meinal = OCR) |
| Floyd D Brewer | `Related/Floyd-D-Brewer` + `Related/Flord-D-Brewer` | Floyd / Flord |
| Frank Patrick Jobin | `Related/Frank-P-Jobin-Jr-1879` + `Related/Frank-Patrick-Jobin` + `Related/Frank-Patrick-Tobin-Sr-1879` | Jobin/Tobin, both b. Feb 11 1879 — verify Jr/Sr |
| Charlotte Kay Tiel | `Related/Charlotte-Kay-Tie` + `Related/Charlotte-Kay-Tiel` | Tie / Tiel (wife of Donald VerBerkmoes) |
| Daniel Pitts | `Related/Daniel-Pitts` + `Related/Danil-Pitts` | Daniel / Danil |
| Henry TerArchter | `Related/Henry-Ter-Archer` + `Related/Henry-TerArchter` | married Gertrude, Jan 14 1908 |
| Mildred Charlotte TerArchter | `Related/Mildred-Charlotte-TerAcher` + `Related/Mildred-Charlotte-TerArchter-1910` | TerAcher / TerArchter |
| Marinus Wisse | `Related/Marinus-Wise-1890` + `Related/Marinus-Wisse-2` | Wise / Wisse (father of Frans Wisse) |
| Stella Mary Claflin | `Related/Stella-Mary-Claflin-1898` + `Related/Stella-Mary-Claftin` | Claflin / Claftin |
| William Mil Flemming | `Related/William-Mil-Fleming-1908` + `Related/William-Mil-Flemming` | Fleming / Flemming (b.1908 / d.1981) |
| Kenneth Duane Westgate | `Related/Kenneth-Duane-Westgate-1946` + `Related/Kennith-Duane-Westgate` | Kenneth / Kennith |
| Wililda "Ida" Caulkins | `Related/Wililda-Calkins-Howard` + `Related/Wililda-L-Ida-Caulkins` | Calkins / Caulkins (married Howard) |
| Eugene Simons | `Related/Eugene-A-Simmons-2` + `Related/Eugene-Simons-1904` | Simmons / Simons |
| Hendrika F van der Nood | `Related/Hendrika-F-van-der-Nood-van-Drunen` + `Related/Hendrika-Francia-Der-Nood-1856` | |
| Derkje Adriaansd Schippers | `Related/Derkje-Adriaansd` + `Related/Derkje-Adriaansd-Schippers-1819` | |
| Jacoba (Cora) Roozendaal | `Related/Jacoba-Cora-Tobiasd-Roozendaal-1860` + `Related/Jacoba-Roozendall` | Roozendaal / Roozendall |
| Pieternella Jacoba Botbijl | `Related/Pieternella-Jacoba` + `Related/Pieternella-Jacoba-Hendriksd-Botbijl-1862` | |
| Magdalena Van Der Plassche | `Related/Magdalena-Van-Der-Plassche-1889` + `Related/Magdalena-VanDerPlassche` + `Related/MagDelena-VanDerPlassche` | 3 → 1; check `Related/Lena-Vander-Plassche` (m.1907) — may be same |
| Johannes Fredrick Hieftje | `Related/Johannes-Fredrick-Heifjte` | *Heifjte* OCR of *Hieftje* — cross-check vs other Hieftje notes |

## C. Redundant / exact same-person notes — HIGH confidence

| Person | Notes to merge | Note |
|---|---|---|
| William VerBerkmoes (b. May 5 1883) | `VerBerkmoes/William-VerBerkmoes-1883` + `VerBerkmoes/William-VerBerkmoes-1883-2` | exact duplicate (*`-1888` is a different William — keep*) |
| Joseph Herbert VerBerkmoes (b. Dec 3 1891) | `VerBerkmoes/Joseph-Herbert-VerBerkmoes-1891` + `VerBerkmoes/Joseph-Herbert-VerBerkmoes-Sr-1891` | same man (*`Jr-1923` is the son — keep*) |
| Cornelis Adriaansz VerBerkmoes (b. Jan 1854) | `VerBerkmoes/Cornelis-Adriaansz-VerBerkmoes-1854` + `VerBerkmoes/Cornelius-Adriaansz-VerBerkmoes-1854` | Cornelis/Cornelius (*`-6-mons` infant and `Cornelis-Verberkmoes-1858` are different — keep*) |
| Robert Edward Culver VerBerkmoes (b. Aug 4 1937) | `VerBerkmoes/Robert-Edward-Culver-VerBerkmoes-1937` + `Related/Robert-Edward-1937` | same man |
| James William Rezny (b. Sep 8 1942) | `Related/James-William-Rezny-1942` + `Related/James-William-Rezny-Grand-Haven-1942` | same man |
| George McNamara | `Related/George-McNamara` + `Related/George-McNamara-G-H-MI` | latter is a marriage-event fragment |
| Edith Rose | `Related/Edith-Rose` + `Related/Edith-Rose-Grand-Haven-MI` | latter is a marriage-event fragment |
| Frieda Emma Christine Lewke | `Related/Frieda-Emma-Christine-Lewke` + `Related/Frieda-E-C-Lewke-Lake-Cnty-Indiana` | latter is a marriage-event fragment |
| Wendy Lee Crum | `Related/Wendy-Lee-Crum-1965` + `Related/Wenndy-Lee-Crum-Vail` | Wendy / Wenndy |

## D. Probable duplicates — PLEASE CONFIRM (judgment required)

- **Kelly Ann Bryant** `Related/Kelly-Ann-Bryant-1961` vs **Kelly Ann Snoek** `Snoek/Kelly-Ann-Snoek-1961` — same b.1961; likely maiden/married, but confirm she isn't a different relative.
- **Doris Bosselman** `Related/Doris-Bosseiman` (Snoek children) vs `Related/Doris-Bosselman` (child Robin Bosselman) — *Bosseiman* is OCR of *Bosselman*, but the two notes list **different children**. Same woman with two marriages, or two different women?
- **Cecelia/Cecilla Brosseit** `Related/Cecelia-Brosseit` (mother of Jack & Robert Phipps) vs `Related/Cecilla-Brosseit-1945` (b.1945) — probably the same (note also `Related/Allen-D-Phipps` lists the same two Phipps children).
- **Joan Advent** `Related/Joan-Advent-Babaut-1556` (b.1556) vs `Related/Joan-Avent-1560` (b.1560) vs `Coffin/Joan-Advent-Coffin` (d.) — Advent/Avent, birth years differ by 4; likely one woman across 3 notes.
- **Jeanette** cluster: `Related/Jeanette` (m.1920) / `Related/Jeanette-unknown` (m.1920 Chicago) / `VerBerkmoes/Jeanette-VerBerkmoes` (d.1923 Chicago) — at least the two 1920-marriage stubs look identical; verify against the VerBerkmoes note.
- **Kryn / Krien / Krijn VerBerkmoes** — large multi-generation naming knot:
  `Kryn-Krien-VerBerkmoes` (d.1894), `Krien-VerBerkmoes-Sr-1894` (b.1894), `Krien-VerBerkmoes-Jr-1924`,
  `Krijn-Krien-Adriaansz-VerBerkmoes-1860`, `Krien-VerBerkmoes` (son of Krien & Edith Plant),
  `Krijn-VerBerkmoes-4-mons-13-dys` (infant). These are **not all the same** — needs a careful
  generation-by-generation pass before merging.
- **William Faranick / Farfanick** `Related/William-Faranick` vs `Related/William-George-Farfanick-1944` — the first is listed as **father** of the second, so these are likely **two people** (keep both) with an inconsistent surname spelling to reconcile.

## E. Non-person extraction artifacts (probably should not be People at all)

These were created from place/event lines, not individuals. Suggest removing from `01-People` or
recategorizing (places → `02-Places`, headlines → `03-Historical-Context`):

- Places / directories: `Related/Grand-Haven-MI`, `Related/Grand-Haven-Ottawa-Cnty-Michigan`,
  `Related/Grand-Rapids`, `Related/Ferrysburg`, `Related/Upjohn-Blk`, `Related/h-7458-N-Polk`
- Cemeteries: `Related/Green-Ridge-Cemetery`, `Related/Moss-Ridge-Cemetery`
- Migration/event lines: `Related/from-Goes-Zeeland-Netherlands`, `Related/to-AMERICA`,
  `Related/Draft-Registration`, `VerBerkmoes/Leonard-VerBerkmoes-Spring-Lake-MI` (WWII draft line)
- Historical headlines: `Related/Former-President-John-Adams-died-at-the-age-of-91`,
  `Related/Chief-Joseph-Wakazoo-passes-away`

## F. Placeholder / unnamed-child nodes that appear duplicated

Each pair/triple below shares identical parents and no distinguishing data — likely the generator
emitted the same unnamed child more than once (or they are genuinely separate siblings — confirm):

- `Related/name-Damp`, `name-Damp-2`, `name-Damp-3` (parents Derick K Damp & Alisha Ranft)
- `Related/name-Ranft`, `name-Ranft-2` (parents Chad Ranft & Jennie)
- `Related/child-Gann`, `child-Gann-2` (father Josuha Gann)
- `Related/daughter-Brown`, `daughter-Brown-2`, `daughter-Brown-3` (father Riley Brown)
- `Related/son-Eastling`, `son-Eastling-2` (mother Valeri Eastling)
- `Related/stepson`, `stepson-2` (linked to the `Tamie-name` / `Tammie-name` pair below)
- `Related/Tamie-name`, `Related/Tammie-name` (both "Children: stepson")

## Tallies (approximate)

- Section A (maiden/married): ~23 clusters, ~48 notes → ~23
- Section B (spelling/OCR): ~25 clusters, ~55 notes → ~25
- Section C (redundant): ~9 clusters, ~18 notes → ~9
- Section E (non-person): ~14 notes to remove/recategorize
- Sections D & F: flagged for your confirmation

**Net:** roughly **90–110 of the 829 person pages are duplicates or non-persons.** Resolving A–C
and E alone removes on the order of **80+ redundant notes**.

---

*Audit generated from a full read of every `01-People` page. Apply merges in the source vault, then
rebuild the site. Sections D and F deliberately defer to your judgement rather than guess.*
