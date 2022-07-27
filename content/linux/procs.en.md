---
author: ['Navneet Aman']
date: 1628437549
title: "procs, TLDR Pages"
description: "procs, Display information about the active processes."
categories: "linux"
---
> More information: <https://github.com/dalance/procs>.

- List all processes showing the PID, user, CPU usage, memory usage, and the command which started them:

```bash
procs
```

- Show information about processes, if the commands which started them contain `zsh`:

```bash
procs zsh
```

- Show information about all processes sorted by CPU time in [a]scending or [d]escending order:

```bash
procs --sortd|--sorta cpu
```

- Show information about processes with either a PID, command, or user containing (`zsh` or `firefox`):

```bash
procs --or PID|command|user 41 firefox
```

- Show information about processes with both PID `41` and a command or user containing `zsh`:

```bash
procs --and 41 zsh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Navneet Aman](mailto:navneetankur@gmail.com) | procs: add page (#6274) | 2021-08-08T17:45:49 | [7927398de440](https://github.com/tldr-pages/tldr/commit/7927398de4403ec40ed0a239c289fba00b0ee48d)

