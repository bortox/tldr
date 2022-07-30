---
author: ['git-em']
date: 1645869632
title: "ncdu"
description: "ncdu, Disk usage analyzer with an ncurses interface."
categories: "common"
---
> More information: <https://manned.org/ncdu>.

- Analyze the current working directory:

```bash
ncdu
```

- Colorize output:

```bash
ncdu --color dark|off
```

- Analyze a given directory:

```bash
ncdu path/to/directory
```

- Save results to a file:

```bash
ncdu -o path/to/file
```

- Exclude files that match a pattern, argument can be given multiple times to add more patterns:

```bash
ncdu --exclude '*.txt'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | ncdu: move from linux to common (#7814) | 2022-02-26T11:00:32 | [a5276a09e03d](https://github.com/tldr-pages/tldr/commit/a5276a09e03d20fb07c23b5f268f0e62a0e4c5dd)

