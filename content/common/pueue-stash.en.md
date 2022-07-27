---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue stash, TLDR Pages"
description: "pueue stash, Stash tasks to prevent them starting automatically."
categories: "common"
---
> See also `pueue start` and `pueue enqueue`.

> More information: <https://github.com/Nukesor/pueue>.

- Stash an enqueued task:

```bash
pueue stash task_id
```

- Stash multiple tasks at once:

```bash
pueue stash task_id task_id
```

- Start a stashed task immediately:

```bash
pueue start task_id
```

- Enqueue a task to be executed when preceding tasks finish:

```bash
pueue enqueue task_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

