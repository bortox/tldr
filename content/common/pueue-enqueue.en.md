---
author: ['Anas sheashaey']
date: 1617129316
title: "pueue enqueue, TLDR Pages"
description: "pueue enqueue, Enqueue stashed tasks."
categories: "common"
---
> See also: `pueue stash`.

> More information: <https://github.com/Nukesor/pueue>.

- Enqueue multiple stashed tasks at once:

```bash
pueue enqueue task_id task_id
```

- Enqueue a stashed task after 60 seconds:

```bash
pueue enqueue --delay 60 task_id
```

- Enqueue a stashed task next Wednesday:

```bash
pueue enqueue --delay wednesday task_id
```

- Enqueue a stashed task after four months:

```bash
pueue enqueue --delay "4 months" task_id
```

- Enqueue a stashed task on 2021-02-19:

```bash
pueue enqueue --delay 2021-02-19 task_id
```

- List all available date/time formats:

```bash
pueue enqueue --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anas sheashaey](mailto:she3sha3y5@gmail.com) | pueue-*: add page (#5285) | 2021-03-30T20:35:16 | [7a539443844b](https://github.com/tldr-pages/tldr/commit/7a539443844bfce6772ba0b2d829ca8e7b9934da)

