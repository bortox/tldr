---
author: ['Guilherme Silva']
date: 1574704245
title: "csvkit"
description: "csvkit, Manipulation toolkit for CSV files."
categories: "common"
---
> See the individual commands: `csvclean`, `csvcut`, `csvformat`, `csvgrep`, `csvlook`, `csvpy`, `csvsort`, `csvstat`.

> More information: <https://csvkit.readthedocs.io/en/0.9.1/cli.html>.

- Run a command on a CSV file with a custom delimiter:

```bash
cmd -d delimiter filename.csv
```

- Run a command on a CSV file with a tab as a delimiter (overrides -d):

```bash
cmd -t filename.csv
```

- Run a command on a CSV file with a custom quote character:

```bash
cmd -q quote_char filename.csv
```

- Run a command on a CSV file with no header row:

```bash
cmd -H filename.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guilherme Silva](mailto:guilhermejosesilva@gmail.com) | csvkit: add page (#3386) | 2019-11-25T18:50:45 | [a8b4159c9b61](https://github.com/tldr-pages/tldr/commit/a8b4159c9b611739307e6afea1f05856f2752b84)

