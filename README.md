# Data for reptile diversity paper

## Overview

This repository contains the three data tables referenced in the following paper:

> Pua Bar (Kutiel), Michael Dorman, Boaz Shacham. [Year]. *Reptile diversity and composition at urban-rural edge zones along the Mediterranean coastal dunes of Israel*. [Journal Name]. [DOI / link]

## Repository contents

Other than this document (`README.md`), the repository contains three data tables:

* `table_01.csv`---Raw reptile counts
* `table_02.csv`---Species names abbreviations
* `table_03.csv`---Abundance ranks

Printouts of the table structure and description of the columns are given in the next section.

## Table Descriptions

### `table_01.csv` --- Raw reptile counts

```{text}
      year                       point protocol species  count
0     2015  Ashdod Far Semi-Shifting 1     scan     A.s      2
1     2015  Ashdod Far Semi-Shifting 1     scan     C.s      1
2     2015  Ashdod Far Semi-Shifting 1     scan     S.d      1
3     2015  Ashdod Far Semi-Shifting 1    trail     S.s      1
4     2015  Ashdod Far Semi-Shifting 2     scan     A.s      1
...    ...                         ...      ...     ...    ...
1165  2025  Zikim Near Semi-Shifting 3     scan     A.s      4
1166  2025  Zikim Near Semi-Shifting 3     scan     P.s      1
1167  2025  Zikim Near Semi-Shifting 3    trail     C.o      5
1168  2025  Zikim Near Semi-Shifting 3    trail     C.s      8
1169  2025  Zikim Near Semi-Shifting 3    trail     S.s      4

[1170 rows x 5 columns]
```

* `year`---Sampling year
* `point`---Location ID
* `protocol`---Sampling method
* `species`---Species
* `count`---Number of observation

### `table_02.csv` --- Species names abbreviations

```{text}
                         species species2
0    Acanthodactylus scutellatus      A.s
1            Chalcides sepsoides      C.s
2          Spalerosophis diadema      S.d
3   Stenodactylus sthenodactylus      S.s
4            Psammophis schokari      P.s
..                           ...      ...
18           Malpolon insignitus      M.i
19         Ablepharus rueppellii      A.r
20         Dolichophis jugularis      D.j
21     Acanthodactylus aegyptius      A.a
22           Trachylepis vittata     T.vi

[23 rows x 2 columns]
```

* `species`---Full name
* `species2`---Abbreviation

### `table_03.csv` --- Abundance ranks

```{text}
     year    site  point settlements          dunes  ...  S.s  T.g  T.vi  V.g  X.s
0    2015  Ashdod      1         Far  Semi-Shifting  ...  1.0  0.0   0.0  0.0  0.0
1    2015  Ashdod      2         Far  Semi-Shifting  ...  1.0  0.0   0.0  0.0  0.0
2    2015  Ashdod      3         Far  Semi-Shifting  ...  4.0  0.0   0.0  0.0  0.0
3    2015  Ashdod      1         Far       Shifting  ...  1.0  0.0   0.0  0.0  0.0
4    2015  Ashdod      2         Far       Shifting  ...  1.0  0.0   0.0  0.0  0.0
..    ...     ...    ...         ...            ...  ...  ...  ...   ...  ...  ...
210  2025   Zikim      2         Far       Shifting  ...  4.0  0.0   0.0  0.0  0.0
211  2025   Zikim      3         Far       Shifting  ...  3.0  0.0   0.0  0.0  0.0
212  2025   Zikim      1        Near  Semi-Shifting  ...  3.0  0.0   0.0  0.0  0.0
213  2025   Zikim      2        Near  Semi-Shifting  ...  0.0  0.0   0.0  0.0  0.0
214  2025   Zikim      3        Near  Semi-Shifting  ...  3.0  0.0   0.0  0.0  0.0

[215 rows x 28 columns]
```

* `'year'`---Sampling year
* `'site'`---Site
` `'point'`---Location ID
* `'settlements'`---Proximity to settlements
* `'dunes'`---Dune type
* `'A.a'`...`'X.s'`---Species



