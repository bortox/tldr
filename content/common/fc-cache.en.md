---
author: ['marchersimon']
date: 1631539539
title: "fc-cache, TLDR Pages"
description: "fc-cache, Scan font directories to build font cache files."
categories: "common"
---
> More information: <https://manned.org/fc-cache>.

- Generate font cache files:

```bash
fc-cache
```

- Force a rebuild of all font cache files, without checking if cache is up-to-date:

```bash
fc-cache -f
```

- Erase font cache files, then generate new font cache files:

```bash
fc-cache -r
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fc*: move to common (#6510) | 2021-09-13T15:25:39 | [7786008d9e1d](https://github.com/tldr-pages/tldr/commit/7786008d9e1d2b3ffa31c3e95ac0127e42466190)

