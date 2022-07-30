---
author: ['marchersimon']
date: 1631539539
title: "fc-list"
description: "fc-list, List available fonts installed on the system."
categories: "common"
---
> More information: <https://manned.org/fc-list>.

- Return a list of installed fonts in your system:

```bash
fc-list
```

- Return a list of installed fonts with given name:

```bash
fc-list | grep 'DejaVu Serif'
```

- Return the number of installed fonts in your system:

```bash
fc-list | wc -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fc*: move to common (#6510) | 2021-09-13T15:25:39 | [7786008d9e1d](https://github.com/tldr-pages/tldr/commit/7786008d9e1d2b3ffa31c3e95ac0127e42466190)

