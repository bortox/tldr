---
author: ['pxgamer', 'Hayden Schiff']
date: 1560099229
title: "csvsort, TLDR Pages"
description: "csvsort, Sorts CSV files."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvsort.html>.

- Sort a CSV file by column 9:

```bash
csvsort -c 9 data.csv
```

- Sort a CSV file by the "name" column in descending order:

```bash
csvsort -r -c name data.csv
```

- Sort a CSV file by column 2, then by column 4:

```bash
csvsort -c 2,4 data.csv
```

- Sort a CSV file without inferring data types:

```bash
csvsort --no-inference -c columns data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | csvsort: add link to homepage | 2019-06-09T18:53:49 | [63873e186ef4](https://github.com/tldr-pages/tldr/commit/63873e186ef4c431471f92ece1b8f8f9588eddb4)
[Hayden Schiff](mailto:oxguy3@gmail.com) | typo fix | 2016-01-22T00:16:56 | [5c3c6f9e081b](https://github.com/tldr-pages/tldr/commit/5c3c6f9e081bae21a9510ee46925c0175ff0104b)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added csvsort | 2016-01-22T00:04:19 | [4746a7342c19](https://github.com/tldr-pages/tldr/commit/4746a7342c194b683aaaad1ba0adc043ad99719c)

