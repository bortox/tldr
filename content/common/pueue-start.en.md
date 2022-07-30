---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue start"
description: "pueue start, Resume operation of specific tasks or groups of tasks."
categories: "common"
---
> See also: `pueue pause`.

> More information: <https://github.com/Nukesor/pueue>.

- Resume all tasks in the default group:

```bash
pueue start
```

- Resume a specific task:

```bash
pueue start task_id
```

- Resume multiple tasks at once:

```bash
pueue start task_id task_id
```

- Resume all tasks and start their children:

```bash
pueue start --all --children
```

- Resume all tasks in a specific group:

```bash
pueue start group group_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

