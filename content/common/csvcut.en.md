---
author: ['Hayden Schiff', 'pxgamer']
date: 1560099229
title: "csvcut"
description: "csvcut, Filter and truncate CSV files. Like Unix's `cut` command, but for tabular data."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvcut.html>.

- Print indices and names of all columns:

```bash
csvcut -n data.csv
```

- Extract the first and third columns:

```bash
csvcut -c 1,3 data.csv
```

- Extract all columns **except** the fourth one:

```bash
csvcut -C 4 data.csv
```

- Extract the columns named "id" and "first name" (in that order):

```bash
csvcut -c id,"first name" data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | csvcut: add link to homepage | 2019-06-09T18:53:49 | [9edc31940464](https://github.com/tldr-pages/tldr/commit/9edc31940464c5ec77438e91ff443d1bd654cd51)
[Hayden Schiff](mailto:oxguy3@gmail.com) | csvcut: formatting cleanup | 2016-01-28T21:11:53 | [ac13221b4179](https://github.com/tldr-pages/tldr/commit/ac13221b4179f8006d621acc9dee5f94ce60d364)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added csvcut | 2016-01-22T00:02:55 | [b3710bc9a155](https://github.com/tldr-pages/tldr/commit/b3710bc9a1557b57883fe4e67b611d769bee694a)

