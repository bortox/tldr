---
author: ['endorama']
date: 1637585444
title: "wdctl"
description: "wdctl, Show the hardware watchdog status."
categories: "linux"
---
> More information: <https://manned.org/wdctl>.

- Display the watchdog status:

```bash
wdctl
```

- Display the watchdog status in a single line in key-value pairs:

```bash
wdctl --oneline
```

- Display only specific watchdog flags (list is driver specific):

```bash
wdctl --flags flag_list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[endorama](mailto:526307+endorama@users.noreply.github.com) | wdctl: add page (#7112) | 2021-11-22T13:50:44 | [b39cdcc602ca](https://github.com/tldr-pages/tldr/commit/b39cdcc602caf4d2cd0ad60b892f466ae0ae006b)

