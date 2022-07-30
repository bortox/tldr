---
author: ['Russ Edwards', 'vapniks', 'pxgamer', 'marchersimon']
date: 1620637392
title: "mlr"
description: "mlr, Miller is like `awk`, `sed`, `cut`, `join`, and `sort` for name-indexed data such as CSV, TSV, and tabular JSON."
categories: "common"
---
> More information: <https://johnkerl.org/miller/doc>.

- Pretty-print a CSV file in a tabular format:

```bash
mlr --icsv --opprint cat example.csv
```

- Receive JSON data and pretty print the output:

```bash
echo '{"hello":"world"}' | mlr --ijson --opprint cat
```

- Sort alphabetically on a field:

```bash
mlr --icsv --opprint sort -f field example.csv
```

- Sort in descending numerical order on a field:

```bash
mlr --icsv --opprint sort -nr field example.csv
```

- Convert CSV to JSON, performing calculations and display those calculations:

```bash
mlr --icsv --ojson put '$newField1 = $oldFieldA/$oldFieldB' example.csv
```

- Receive JSON and format the output as vertical JSON:

```bash
echo '{"hello":"world", "foo":"bar"}' | mlr --ijson --ojson --jvstack cat
```

- Filter lines of a compressed CSV file treating numbers as strings:

```bash
mlr --prepipe 'gunzip' --csv filter -S '$fieldName =~ "regular_expression"' example.csv.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[vapniks](mailto:vapniks@yahoo.com) | mlr: update page (#3623) | 2019-11-30T15:17:34 | [4e589fadf37f](https://github.com/tldr-pages/tldr/commit/4e589fadf37fe0c599c847b93ce6378bbe30f757)
[pxgamer](mailto:owzie123@gmail.com) | mlr: add link to homepage | 2019-06-04T21:29:40 | [6befddced53e](https://github.com/tldr-pages/tldr/commit/6befddced53ee86f798c3d2af3298542d76e1267)
[Russ Edwards](mailto:redwards@digitellinc.com) | mlr: add page (#2434) | 2018-10-16T19:26:42 | [440bfe44c0bb](https://github.com/tldr-pages/tldr/commit/440bfe44c0bbc77816b9f76d4673c2f753164fa4)

