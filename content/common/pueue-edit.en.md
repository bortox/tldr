---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue edit"
description: "pueue edit, Edit the command or path of a stashed or queued task."
categories: "common"
---
> More information: <https://github.com/Nukesor/pueue>.

- Edit a task, see `pueue status` to get the task ID:

```bash
pueue edit task_id
```

- Edit the path from which a task is executed:

```bash
pueue edit task_id --path
```

- Edit a command with the specified editor:

```bash
EDITOR=nano pueue edit task_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

