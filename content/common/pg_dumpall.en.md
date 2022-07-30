---
author: ['George Hafiz']
date: 1642525197
title: "pg_dumpall"
description: "pg_dumpall, Extract a PostgreSQL database cluster into a script file or other archive file."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-pg-dumpall.html>.

- Dump all databases:

```bash
pg_dumpall > path/to/file.sql
```

- Dump all databases using a specific username:

```bash
pg_dumpall --username=username > path/to/file.sql
```

- Same as above, customize host and port:

```bash
pg_dumpall -h host -p port > output_file.sql
```

- Dump all databases into a custom-format archive file with moderate compression:

```bash
pg_dumpall -Fc > output_file.dump
```

- Dump only database data into an SQL-script file:

```bash
pg_dumpall --data-only > path/to/file.sql
```

- Dump only schema (data definitions) into an SQL-script file:

```bash
pg_dumpall -s > output_file.sql
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[George Hafiz](mailto:george@hafiz.uk) | pg_dumpall: add page (#7646) | 2022-01-18T17:59:57 | [f90a84145a8a](https://github.com/tldr-pages/tldr/commit/f90a84145a8a7b60d6b43eef58b7c2ca2ba5f53f)

