---
author: ['Seth Falco', 'Ruben Vereecken', 'Yang-Hsing Lin', 'pxgamer', 'Andrik Albuquerque']
date: 1629050349
title: "pg_dump, TLDR Pages"
description: "pg_dump, Extract a PostgreSQL database into a script file or other archive file."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-pgdump.html>.

- Dump database into an SQL-script file:

```bash
pg_dump db_name > output_file.sql
```

- Same as above, customize username:

```bash
pg_dump -U username db_name > output_file.sql
```

- Same as above, customize host and port:

```bash
pg_dump -h host -p port db_name > output_file.sql
```

- Dump a database into a custom-format archive file:

```bash
pg_dump -Fc db_name > output_file.dump
```

- Dump only database data into an SQL-script file:

```bash
pg_dump -a db_name > path/to/output_file.sql
```

- Dump only schema (data definitions) into an SQL-script file:

```bash
pg_dump -s db_name > path/to/output_file.sql
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | pg_dump: add link to homepage | 2019-05-31T20:47:40 | [e1e401547c5e](https://github.com/tldr-pages/tldr/commit/e1e401547c5e3e39f1b263630c0d50d1568bfa00)
[Andrik Albuquerque](mailto:andrik.albuquerque@gmail.com) | pg_dump: added -a and -s examples (#2856) | 2019-03-30T22:20:05 | [0207fe045a17](https://github.com/tldr-pages/tldr/commit/0207fe045a171443baeef56ae0ae45cb14ef4774)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Yang-Hsing Lin](mailto:yanghsing.lin@gmail.com) | pg_restore/pg_dump: add page | 2016-01-11T16:39:12 | [f4aebf680ad9](https://github.com/tldr-pages/tldr/commit/f4aebf680ad90363fd7d65fa4258a47cffb8bd60)

