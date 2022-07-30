---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue pause"
description: "pueue pause, Pause running tasks or groups."
categories: "common"
---
> See also: `pueue start`.

> More information: <https://github.com/Nukesor/pueue>.

- Pause all tasks in the default group:

```bash
pueue pause
```

- Pause a running task:

```bash
pueue pause task_id
```

- Pause a running task and stop all its direct children:

```bash
pueue pause --children task_id
```

- Pause all tasks in a group and prevent it from starting new tasks:

```bash
pueue pause --group group_name
```

- Pause all tasks and prevent all groups from starting new tasks:

```bash
pueue pause --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

