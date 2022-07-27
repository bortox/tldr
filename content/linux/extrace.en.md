---
author: ['Pierre Rudloff']
date: 1575101333
title: "extrace, TLDR Pages"
description: "extrace, Trace exec() calls."
categories: "linux"
---
> More information: <https://github.com/chneukirchen/extrace>.

- Trace all program executions occurring on the system:

```bash
sudo extrace
```

- Run a command and only trace descendants of this command:

```bash
sudo extrace command
```

- Print the current working directory of each process:

```bash
sudo extrace -d
```

- Resolve the full path of each executable:

```bash
sudo extrace -l
```

- Display the user running each process:

```bash
sudo extrace -u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | extrace: add page | 2019-11-30T09:08:53 | [25783720449b](https://github.com/tldr-pages/tldr/commit/25783720449bad88c3589043d18ff52cd3fcdb2d)

