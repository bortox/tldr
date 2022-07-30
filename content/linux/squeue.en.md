---
author: ['Garrett Mills', 'Emily Grace Seville']
date: 1647882468
title: "squeue"
description: "squeue, View the jobs queued in the SLURM scheduler."
categories: "linux"
---
> More information: <https://manned.org/squeue>.

- View the queue:

```bash
squeue
```

- View jobs queued by a specific user:

```bash
squeue -u username
```

- View the queue and refresh every 5 seconds:

```bash
squeue -i 5
```

- View the queue with expected start times:

```bash
squeue --start
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Garrett Mills](mailto:garrett@glmdev.tech) | squeue: add page (#2598) | 2018-11-18T22:44:08 | [88545ce503bd](https://github.com/tldr-pages/tldr/commit/88545ce503bd3d1ec7b0d2354a3a65bd4198b2a0)

