---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue reset"
description: "pueue reset, Kill everything and reset."
categories: "common"
---
> More information: <https://github.com/Nukesor/pueue>.

- Kill all tasks and remove everything (logs, status, groups, task IDs):

```bash
pueue reset
```

- Kill all tasks, terminate their children, and reset everything:

```bash
pueue reset --children
```

- Reset without asking for confirmation:

```bash
pueue reset --force
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

