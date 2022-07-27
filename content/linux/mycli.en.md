---
author: ['Max Xu', 'Lucas Gabriel Schneider']
date: 1629110041
title: "mycli, TLDR Pages"
description: "mycli, A CLI for MySQL, MariaDB, and Percona with auto-completion and syntax highlighting."
categories: "linux"
---
> More information: <https://manned.org/mycli>.

- Connect to a database with the currently logged in user:

```bash
mycli database_name
```

- Connect to a database with the specified user:

```bash
mycli -u user database_name
```

- Connect to a database on the specified host with the specified user:

```bash
mycli -u user -h host database_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Max Xu](mailto:xuhuan@live.cn) | mycli.md: add page (#1830) | 2017-12-24T21:47:45 | [705e0c8b84e3](https://github.com/tldr-pages/tldr/commit/705e0c8b84e37a9ffd77dc9a0a5e0777c5ff9865)

