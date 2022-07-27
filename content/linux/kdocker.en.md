---
author: ['CleanMachine1']
date: 1621968710
title: "kdocker, TLDR Pages"
description: "kdocker, Easily dock applications to the system tray."
categories: "linux"
---
> More information: <https://github.com/user-none/KDocker>.

- Display a cursor to send a window to the system tray when pressing the left mouse button (press any other mouse button to cancel):

```bash
kdocker
```

- Open an application and send it to the system tray:

```bash
kdocker application
```

- Send focused window to the system tray:

```bash
kdocker -f
```

- Display a cursor to send a window to the system tray with a custom icon when pressing the left mouse button:

```bash
kdocker -i /path/to/icon
```

- Open an application, send it to the system tray and if focus is lost, minimize it:

```bash
kdocker -l application
```

- Print version:

```bash
kdocker --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | kdocker: add page (#6044) | 2021-05-25T20:51:50 | [d45e49f90028](https://github.com/tldr-pages/tldr/commit/d45e49f90028194b1019155bcb5bac3014c2f466)

