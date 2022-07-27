---
author: ['David Heimann', 'Robert Treat', 'pxgamer']
date: 1580309649
title: "pg_ctl, TLDR Pages"
description: "pg_ctl, Utility for controlling a PostgreSQL server and database cluster."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/current/app-pg-ctl.html>.

- Initialize a new PostgreSQL database cluster:

```bash
pg_ctl -D data_directory init
```

- Start a PostgreSQL server:

```bash
pg_ctl -D data_directory start
```

- Stop a PostgreSQL server:

```bash
pg_ctl -D data_directory stop
```

- Restart a PostgreSQL server:

```bash
pg_ctl -D data_directory restart
```

- Reload the PostgreSQL server configuration:

```bash
pg_ctl -D data_directory reload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robert Treat](mailto:xzilla@users.noreply.github.com) | Clean up pg_ctl commands (#3817) - fix command syntax for pg_ctl start - re-arrange commands into a more natural flow - add command [...] | 2020-01-29T15:54:09 | [ca968791e342](https://github.com/tldr-pages/tldr/commit/ca968791e3425c8ee6eb01f8c729c07e76fbbee1)
[pxgamer](mailto:owzie123@gmail.com) | pg_ctl: add link to homepage | 2019-05-31T20:47:40 | [b1c8dfc9d7df](https://github.com/tldr-pages/tldr/commit/b1c8dfc9d7df00bf962280c817a0f58c51c62f71)
[David Heimann](mailto:heimann@users.noreply.github.com) | Add pg_ctl page (#1835) | 2017-12-27T14:55:16 | [22042bb46ee8](https://github.com/tldr-pages/tldr/commit/22042bb46ee8034072b31cc1162feffb2f8adcc0)

