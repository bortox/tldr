---
author: ['Managor']
date: 1636096289
title: "localectl"
description: "localectl, Control the system locale and keyboard layout settings."
categories: "linux"
---
> More information: <https://www.freedesktop.org/software/systemd/man/localectl.html>.

- Show the current settings of the system locale and keyboard mapping:

```bash
localectl
```

- List available locales:

```bash
localectl list-locales
```

- Set a system locale variable:

```bash
localectl set-locale LANG=en_US.UTF-8
```

- List available keymaps:

```bash
localectl list-keymaps
```

- Set the system keyboard mapping for the console and X11:

```bash
localectl set-keymap us
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | localectl: add page (#7272) | 2021-11-05T08:11:29 | [2bb4916d8329](https://github.com/tldr-pages/tldr/commit/2bb4916d83292aabeb0618acca815ffcf899d001)

