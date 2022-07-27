---
author: ['Anay Nayak']
date: 1635805974
title: "textql, TLDR Pages"
description: "textql, Execute SQL against structured text like csv or tsv files."
categories: "common"
---
> More information: <https://github.com/dinedal/textql>.

- Print the lines in the specified `.csv` file that match a SQL query to stdout:

```bash
textql -sql "SELECT * FROM filename" path/to/filename.csv
```

- Query `.tsv` file:

```bash
textql -dlm=tab -sql "SELECT * FROM filename" path/to/filename.tsv
```

- Query file with header row:

```bash
textql -dlm=delimiter -header -sql "SELECT * FROM filename" path/to/filename.csv
```

- Read data from stdin:

```bash
cat path/to/file | textql -sql "SELECT * FROM stdin"
```

- Join two files on a specified common column:

```bash
textql -header -sql "SELECT * FROM file1 JOIN file2 ON file1.c1 = file2.c1 LIMIT 10" -output-header path/to/file1.csv path/to/file2.csv
```

- Format output using an output delimiter with an output header line:

```bash
textql -output-dlm=delimiter -output-header -sql "SELECT column AS alias FROM filename" path/to/filename.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anay Nayak](mailto:anaynayak@users.noreply.github.com) | textql: add page (#7154) | 2021-11-01T23:32:54 | [5c5042a6c460](https://github.com/tldr-pages/tldr/commit/5c5042a6c46059d2fb66ee12617017d8ae970ef0)

