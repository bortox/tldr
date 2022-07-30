---
author: ['Emily Grace Seville', 'lbonanomi']
date: 1647882468
title: "script"
description: "script, Record all terminal output to file."
categories: "linux"
---
> More information: <https://manned.org/script>.

- Record a new session to a file named `typescript` in the current directory:

```bash
script
```

- Record a new session to a custom filepath:

```bash
script path/to/session.out
```

- Record a new session, appending to an existing file:

```bash
script -a path/to/session.out
```

- Record timing information (data is outputted to the standard error):

```bash
script -t 2> path/to/timingfile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | script: add page (#2918) | 2019-04-16T02:54:52 | [80abec2c14a7](https://github.com/tldr-pages/tldr/commit/80abec2c14a73b27bf2dc379113e87f19d15f94d)

