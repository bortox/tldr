---
author: ['Andy Atkinson', 'Nainterceptor']
date: 1616431551
title: "pgbench"
description: "pgbench, Run a benchmark test on PostgreSQL."
categories: "common"
---
> More information: <https://www.postgresql.org/docs/10/pgbench.html>.

- Initialize a database with a scale factor of 50 times the default size:

```bash
pgbench --initialize --scale=50 database_name
```

- Benchmark a database with 10 clients, 2 worker threads, and 10,000 transactions per client:

```bash
pgbench --client=10 --jobs=2 --transactions=10000 database_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nainterceptor](mailto:gael@demette.fr) | pgbench: fix typo in --client example (#5487) | 2021-03-22T17:45:51 | [89c193bebabd](https://github.com/tldr-pages/tldr/commit/89c193bebabd8226c6859c6771d17cf9a07f6103)
[Andy Atkinson](mailto:andyatkinson@gmail.com) | pgbench: add page (#5388) | 2021-03-09T22:04:17 | [fb0d9dd7dda7](https://github.com/tldr-pages/tldr/commit/fb0d9dd7dda74855dbf0cae4fd610ac0c8d81d0f)

