---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue restart"
description: "pueue restart, Restart tasks."
categories: "common"
---
> More information: <https://github.com/Nukesor/pueue>.

- Restart a specific task:

```bash
pueue restart task_id
```

- Restart multiple tasks at once, and start them immediately (do not enqueue):

```bash
pueue restart --start-immediately task_id task_id
```

- Restart a specific task from a different path:

```bash
pueue restart --edit-path task_id
```

- Edit a command before restarting:

```bash
pueue restart --edit task_id
```

- Restart a task in-place (without enqueuing as a separate task):

```bash
pueue restart --in-place task_id
```

- Restart all failed tasks and stash them:

```bash
pueue restart --all-failed --stashed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

