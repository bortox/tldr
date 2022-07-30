---
author: ['Fabian Nick', 'Emily Grace Seville']
date: 1647882468
title: "qsub"
description: "qsub, Submits a script to the queue management system TORQUE."
categories: "linux"
---
> More information: <https://manned.org/qsub.1>.

- Submit a script with default settings (depends on TORQUE settings):

```bash
qsub script.sh
```

- Submit a script with a specified wallclock runtime limit of 1 hour, 2 minutes and 3 seconds:

```bash
qsub -l walltime=1:2:3 script.sh
```

- Submit a script that is executed on 2 nodes using 4 cores per node:

```bash
qsub -l nodes=2:ppn=4 script.sh
```

- Submit a script to a specific queue. Note that different queues can have different maximum and minimum runtime limits:

```bash
qsub -q queue_name script.sh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Fabian Nick](mailto:fp.nick@gmail.com) | qsub: add page (#1700) | 2017-12-01T16:29:46 | [e29e511da6eb](https://github.com/tldr-pages/tldr/commit/e29e511da6ebd537818dd60e271c4f8d148842f8)

