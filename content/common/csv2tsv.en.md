---
author: ['Cornelius Roemer']
date: 1661741487
title: "csv2tsv"
description: "csv2tsv, Convert CSV (comma-separated) text to TSV (tab-separated) format."
categories: "common"
---
> More information: <https://github.com/eBay/tsv-utils/blob/master/README.md#csv2tsv>.

- Convert from CSV to TSV:

```bash
csv2tsv path/to/input_csv1 path/to/input_csv2 ... > path/to/output_tsv
```

- Convert field delimiter separated CSV to TSV:

```bash
csv2tsv -c'field_delimiter' path/to/input_csv
```

- Convert semicolon separated CSV to TSV:

```bash
csv2tsv -c';' path/to/input_csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cornelius Roemer](mailto:cornelius.roemer@gmail.com) | csv2tsv: add page (#8407) * add page: csv2tsv * Update pages/common/csv2tsv.md | 2022-08-29T04:51:27 | [a79479c286e7](https://github.com/tldr-pages/tldr/commit/a79479c286e70fe76d0639b2cec62cf5f8b2103e)

