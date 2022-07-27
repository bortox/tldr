---
author: ['derNiklaas', 'marchersimon']
date: 1633404950
title: "whereis, TLDR Pages"
description: "whereis, Locate the binary, source, and manual page files for a command."
categories: "common"
---
> More information: <https://manned.org/whereis>.

- Locate binary, source and man pages for ssh:

```bash
whereis ssh
```

- Locate binary and man pages for ls:

```bash
whereis -bm ls
```

- Locate source of gcc and man pages for Git:

```bash
whereis -s gcc -m git
```

- Locate binaries for gcc in `/usr/bin/` only:

```bash
whereis -b -B /usr/bin/ -f gcc
```

- Locate unusual binaries (those that have more or less than one binary on the system):

```bash
whereis -u *
```

- Locate binaries that have unusual manual entries (binaries that have more or less than one manual installed):

```bash
whereis -u -m *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | whereis, xar, yank: move to common (#6552) | 2021-09-19T02:59:20 | [e94e6af88289](https://github.com/tldr-pages/tldr/commit/e94e6af88289f26bf25c85b45971f240f56d8672)

