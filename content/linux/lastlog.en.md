---
author: ['Max Xu', 'Lucas Gabriel Schneider', 'Seth Falco', 'marchersimon']
date: 1634849018
title: "lastlog"
description: "lastlog, Show the most recent login of all users or of a given user."
categories: "linux"
---
> More information: <https://manned.org/lastlog>.

- Display the most recent login of all users:

```bash
lastlog
```

- Display the lastlog record of the specified user:

```bash
lastlog --user username
```

- Display records older than 7 days:

```bash
lastlog --before 7
```

- Display records more recent than 3 days:

```bash
lastlog -time 3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | lastlog: refresh (#7133) | 2021-10-21T22:43:38 | [254a2f9ae7f7](https://github.com/tldr-pages/tldr/commit/254a2f9ae7f7eb67b661ff3d17f097159ac8a397)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Max Xu](mailto:xuhuan@live.cn) | lastlog.md: add page (#1817) | 2017-12-19T16:26:37 | [5748e7cdae30](https://github.com/tldr-pages/tldr/commit/5748e7cdae301656db346418d09907c1ba9a1a49)

