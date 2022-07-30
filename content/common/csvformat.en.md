---
author: ['Hayden Schiff', 'pxgamer']
date: 1560099229
title: "csvformat"
description: "csvformat, Convert a CSV file to a custom output format."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvformat.html>.

- Convert to a tab-delimited file (TSV):

```bash
csvformat -T data.csv
```

- Convert delimiters to a custom character:

```bash
csvformat -D "custom_character" data.csv
```

- Convert line endings to carriage return (^M) + line feed:

```bash
csvformat -M "\r\n" data.csv
```

- Minimize use of quote characters:

```bash
csvformat -U 0 data.csv
```

- Maximize use of quote characters:

```bash
csvformat -U 1 data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | csvformat: add link to homepage | 2019-06-09T18:53:49 | [828c910d89a3](https://github.com/tldr-pages/tldr/commit/828c910d89a3685235b2a478b44611bfb74fdc80)
[Hayden Schiff](mailto:oxguy3@gmail.com) | csvformat: better wording and clarifications | 2016-01-28T21:08:47 | [749ca0897dd6](https://github.com/tldr-pages/tldr/commit/749ca0897dd640c043d93317cf5e696c6bed6297)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added csvformat | 2016-01-22T00:03:08 | [7f5bc2fec7be](https://github.com/tldr-pages/tldr/commit/7f5bc2fec7beee2453ff1bdfc1811d9936292c8d)

