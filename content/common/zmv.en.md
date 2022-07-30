---
author: ['hrai', 'marchersimon']
date: 1620637392
title: "zmv"
description: "zmv, Move or rename files matching a specified extended glob pattern."
categories: "common"
---
> See also `zcp` and `zln`.

> More information: <http://zsh.sourceforge.net/Doc/Release/User-Contributions.html>.

- Move files using a regular expression-like pattern:

```bash
zmv '(*).log' '$1.txt'
```

- Preview the result of a move, without making any actual changes:

```bash
zmv -n '(*).log' '$1.txt'
```

- Interactively move files, with a prompt before every change:

```bash
zmv -i '(*).log' '$1.txt'
```

- Verbosely print each action as it's being executed:

```bash
zmv -v '(*).log' '$1.txt'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[hrai](mailto:4055444+hrai@users.noreply.github.com) | zmv: add page (#4705) | 2020-12-03T16:55:36 | [b3c0007b1c71](https://github.com/tldr-pages/tldr/commit/b3c0007b1c7164bd70e700b0824071864bdaa39e)

