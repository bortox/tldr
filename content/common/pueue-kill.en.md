---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue kill"
description: "pueue kill, Kill running tasks or whole groups."
categories: "common"
---
> More information: <https://github.com/Nukesor/pueue>.

- Kill all tasks in the default group:

```bash
pueue kill
```

- Kill a specific task:

```bash
pueue kill task_id
```

- Kill a task and terminate all its child processes:

```bash
pueue kill --children task_id
```

- Kill all tasks in a group and pause the group:

```bash
pueue kill --group group_name
```

- Kill all tasks across all groups and pause all groups:

```bash
pueue kill --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

