---
author: ['CleanMachine1']
date: 1661318831
title: "daemon"
description: "daemon, Run processes into daemons."
categories: "linux"
---
> More information: <https://manned.org/man/daemon.1>.

- Run a command as a daemon:

```bash
daemon --name="name" command
```

- Run a command as a daemon which will restart if the command crashes:

```bash
daemon --name="name" --respawn command
```

- Run a command as a daemon which will restart if it crashes, with two attempts every 10 seconds:

```bash
daemon --name="name" --respawn --attempts=2 --delay=10 command
```

- Run a command as a daemon, writing logs to a specific file:

```bash
daemon --name="name" --errlog=path/to/file.log command
```

- Kill a daemon (SIGTERM):

```bash
daemon --name="name" --stop
```

- List daemons:

```bash
daemon --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | daemon: add page (#8390) * daemon: add page * daemon: add delay example * Update pages/linux/daemon.md Co-authored-by: Axel Navarro [...] | 2022-08-24T07:27:11 | [01f68eb87f2c](https://github.com/tldr-pages/tldr/commit/01f68eb87f2c2f6d24f60d0f4e724b009f58d7d6)

