---
author: ['Seth Falco', 'Benjamin G']
date: 1629050349
title: "schroot, TLDR Pages"
description: "schroot, Run command or start an interactive shell with a different root directory. More customizable than `chroot`."
categories: "linux"
---
> More information: <https://wiki.debian.org/Schroot>.

- Run a command in a specific chroot:

```bash
schroot --chroot chroot command
```

- Run a command with options in a specific chroot:

```bash
schroot --chroot chroot command -- command_options
```

- Run a command in all available chroots:

```bash
schroot --all command
```

- Start an interactive shell within a specific chroot as a specific user:

```bash
schroot --chroot chroot --user user
```

- List available chroots:

```bash
schroot --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Benjamin G](mailto:therealrandomblock1@gmail.com) | schroot: add page (#4775) | 2020-10-29T12:14:20 | [0d2c364b9dba](https://github.com/tldr-pages/tldr/commit/0d2c364b9dbab1428ba5d4f1a5cf348cacaf2f6c)

