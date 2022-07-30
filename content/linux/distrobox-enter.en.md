---
author: ['Mišo Barišić']
date: 1642879685
title: "distrobox-enter"
description: "distrobox-enter, Run a command in a Distrobox container."
categories: "linux"
---
> Default command executed is your SHELL, but you can specify different shells or entire commands to execute. If used inside a script, an application, or a service, you can specify the --headless mode to disable tty and interactivity.

> More information: <https://distrobox.privatedns.org>.

- Enter a distrobox and run `sh -l`:

```bash
distrobox-enter container-name -- sh -l
```

- Enter a distrobox without instantiating a tty:

```bash
distrobox-enter -H container-name -- uptime -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mišo Barišić](mailto:50531162+misobarisic@users.noreply.github.com) | distrobox: add page (#7638) | 2022-01-22T20:28:05 | [26adab31c663](https://github.com/tldr-pages/tldr/commit/26adab31c66345a0ae5fc2deaf410167cbda10ef)

