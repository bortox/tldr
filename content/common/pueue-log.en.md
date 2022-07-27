---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue log, TLDR Pages"
description: "pueue log, Display the log output of 1 or more tasks."
categories: "common"
---
> See also: `pueue status`.

> More information: <https://github.com/Nukesor/pueue>.

- Show the last few lines of output from all tasks:

```bash
pueue log
```

- Show the full output of a task:

```bash
pueue log task_id
```

- Show the last few lines of output from several tasks:

```bash
pueue log task_id task_id
```

- Print a specific number of lines from the tail of output:

```bash
pueue log --lines number_of_lines task_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

