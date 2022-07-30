---
author: ['Max Strübing', 'Lucas Gabriel Schneider']
date: 1629110041
title: "lastb"
description: "lastb, Show a listing of last logged in users."
categories: "linux"
---
> More information: <https://manned.org/lastb>.

- Show a list of all last logged in users:

```bash
sudo lastb
```

- Show a list of all last logged in users since a given time:

```bash
sudo lastb --since YYYY-MM-DD
```

- Show a list of all last logged in users until a given time:

```bash
sudo lastb --until YYYY-MM-DD
```

- Show a list of all logged in users at a specific time:

```bash
sudo lastb --present hh:mm
```

- Show a list of all last logged in users and translate the IP into a hostname:

```bash
sudo lastb --dns
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Max Strübing](mailto:mxstrbng@gmail.com) | lastb: add page (#2645) | 2019-01-28T19:38:12 | [2a11b29c6835](https://github.com/tldr-pages/tldr/commit/2a11b29c6835589a0d446e9e3f17aa82eb4ea622)

