---
author: ['zhangda7', 'pxgamer']
date: 1559676580
title: "ngrep"
description: "ngrep, Filter network traffic packets using regular expressions."
categories: "common"
---
> More information: <https://github.com/jpr5/ngrep>.

- Capture traffic of all interfaces:

```bash
ngrep -d any
```

- Capture traffic of a specific interface:

```bash
ngrep -d eth0
```

- Capture traffic crossing port 22 of interface eth0:

```bash
ngrep -d eth0 port 22
```

- Capture traffic from or to a host:

```bash
ngrep host www.example.com
```

- Filter keyword 'User-Agent:' of interface eth0:

```bash
ngrep -d eth0 'User-Agent:'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | ngrep: add link to homepage | 2019-06-04T21:29:40 | [61baed236b6a](https://github.com/tldr-pages/tldr/commit/61baed236b6a1e72fef399bfa7ff49bdb1241c17)
[zhangda7](mailto:zhangda733@gmail.com) | ngrep: add page (#930) * ngrep: add page * ngrep: update command * ngrep: update syntax | 2016-09-01T17:20:09 | [34aec29c0886](https://github.com/tldr-pages/tldr/commit/34aec29c0886bf0257f7b090af8329c2c7f06dc7)

