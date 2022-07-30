---
author: ['Gil Moskowitz', 'Benjamin Nichols-Farquhar']
date: 1633831225
title: "script"
description: "script, Make a typescript file of a terminal session."
categories: "common"
---
> More information: <https://manned.org/script>.

- Start recording in file named "typescript":

```bash
script
```

- Stop recording:

```bash
exit
```

- Start recording in a given file:

```bash
script logfile.log
```

- Append to an existing file:

```bash
script -a logfile.log
```

- Execute quietly without start and done messages:

```bash
script -q logfile.log
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | script: add more information link (#6911) | 2021-10-10T04:00:25 | [41f8fc70a29d](https://github.com/tldr-pages/tldr/commit/41f8fc70a29dc6361b2c2b16c41f52aa6395ea7a)
[Benjamin Nichols-Farquhar](mailto:bennichols.farquhar@gmail.com) | script: add page (#2485) | 2018-10-28T17:53:06 | [e72e0204feca](https://github.com/tldr-pages/tldr/commit/e72e0204fecaa9b69ce837d4df993ed1b5d75afb)

