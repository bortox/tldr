---
author: ['Hayden Schiff', 'pxgamer']
date: 1559788968
title: "in2csv"
description: "in2csv, Converts various tabular data formats into CSV."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/in2csv.html>.

- Convert an XLS file to CSV:

```bash
in2csv data.xls
```

- Convert a DBF file to a CSV file:

```bash
in2csv data.dbf > data.csv
```

- Convert a specific sheet from an XLSX file to CSV:

```bash
in2csv --sheet=sheet_name data.xlsx
```

- Pipe a JSON file to in2csv:

```bash
cat data.json | in2csv -f json > data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | in2csv: add link to homepage | 2019-06-06T04:42:48 | [da1f99bff6a8](https://github.com/tldr-pages/tldr/commit/da1f99bff6a828e609b3f9ad746809e9069e41e2)
[Hayden Schiff](mailto:oxguy3@gmail.com) | in2csv: better example for piping / `-f` flag | 2016-01-24T08:10:38 | [5676e5892d86](https://github.com/tldr-pages/tldr/commit/5676e5892d86ce67acec5a1712e6012440dd4b6c)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added in2csv | 2016-01-22T00:04:54 | [bb12fba8485e](https://github.com/tldr-pages/tldr/commit/bb12fba8485e0d249022503e22e32ca1722c6707)

