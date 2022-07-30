---
author: ['Pierre Rudloff']
date: 1586969391
title: "csvsql"
description: "csvsql, Generate SQL statements for a CSV file or execute those statements directly on a database."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvsql.html>.

- Generate a `CREATE TABLE` SQL statement for a CSV file:

```bash
csvsql path/to/data.csv
```

- Import a CSV file into an SQL database:

```bash
csvsql --insert --db "mysql://user:password@host/database" data.csv
```

- Run an SQL query on a CSV file:

```bash
csvsql --query "select * from 'data'" data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | csvsql: add page (#3977) | 2020-04-15T18:49:51 | [19cdec56ccdc](https://github.com/tldr-pages/tldr/commit/19cdec56ccdc1a429e45937679b5f4a041af4df1)

