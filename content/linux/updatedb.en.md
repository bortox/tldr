---
author: ['CleanMachine1', 'Flavia Bastos']
date: 1626023849
title: "updatedb, TLDR Pages"
description: "updatedb, Create or update the database used by `locate`."
categories: "linux"
---
> It is usually run daily by cron.

> More information: <https://manned.org/updatedb>.

- Refresh database content:

```bash
sudo updatedb
```

- Display file names as soon as they are found:

```bash
sudo updatedb --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/u*: add links (#6190) | 2021-07-11T19:17:29 | [3ac60f1062ba](https://github.com/tldr-pages/tldr/commit/3ac60f1062ba714b493cee9c4e413901867c9f93)
[Flavia Bastos](mailto:FlaviaBastos@users.noreply.github.com) | updatedb: add page (#2369) | 2018-10-04T12:26:32 | [32f4a2b456bd](https://github.com/tldr-pages/tldr/commit/32f4a2b456bdde4397b98f5f659a98a1e54187e9)

