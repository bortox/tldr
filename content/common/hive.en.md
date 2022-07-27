---
author: ['ktrueda']
date: 1603124939
title: "hive, TLDR Pages"
description: "hive, CLI tool for Apache Hive."
categories: "common"
---
> More information: <https://cwiki.apache.org/confluence/display/Hive/LanguageManual+Cli>.

- Start a Hive interactive shell:

```bash
hive
```

- Run HiveQL:

```bash
hive -e "hiveql_query"
```

- Run a HiveQL file with a variable substitution:

```bash
hive --define key=value -f path/to/file.sql
```

- Run a HiveQL with HiveConfig (e.g. `mapred.reduce.tasks=32`):

```bash
hive --hiveconf conf_name=conf_value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ktrueda](mailto:ktrueda@users.noreply.github.com) | hive: add page (#4632) | 2020-10-19T18:28:59 | [144017572bd5](https://github.com/tldr-pages/tldr/commit/144017572bd5fb75031031604ea7f9dce85a9c3a)

