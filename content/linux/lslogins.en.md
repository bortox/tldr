---
author: ['en1gma713']
date: 1602537362
title: "lslogins, TLDR Pages"
description: "lslogins, Show information about users on a Linux system."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man1/lslogins.1.html>.

- Display users in the system:

```bash
lslogins
```

- Display users belonging to a specific group:

```bash
lslogins --groups=groups
```

- Display user accounts:

```bash
lslogins --user-accs
```

- Display last logins:

```bash
lslogins --last
```

- Display system accounts:

```bash
lslogins --system-accs
```

- Display supplementary groups:

```bash
lslogins --supp-groups
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[en1gma713](mailto:60906502+en1gma713@users.noreply.github.com) | lslogins: add page (#4563) | 2020-10-12T23:16:02 | [4d06885a4f64](https://github.com/tldr-pages/tldr/commit/4d06885a4f645aa552b8e9270c7f8f00c0bf1b04)

