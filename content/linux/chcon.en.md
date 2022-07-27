---
author: ['cyqsimon']
date: 1639653526
title: "chcon, TLDR Pages"
description: "chcon, Change SELinux security context of a file or files/directories."
categories: "linux"
---
> More information: <https://www.gnu.org/software/coreutils/chcon>.

- View security context of a file:

```bash
ls -lZ path/to/file
```

- Change the security context of a target file, using a reference file:

```bash
chcon --reference=reference_file target_file
```

- Change the full SELinux security context of a file:

```bash
chcon user:role:type:range/level filename
```

- Change only the user part of SELinux security context:

```bash
chcon -u user filename
```

- Change only the role part of SELinux security context:

```bash
chcon -r role filename
```

- Change only the type part of SELinux security context:

```bash
chcon -t type filename
```

- Change only the range/level part of SELinux security context:

```bash
chcon -l range/level filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cyqsimon](mailto:28627918+cyqsimon@users.noreply.github.com) | chcon: move from common to linux platform (#7544) | 2021-12-16T12:18:46 | [df0117359b09](https://github.com/tldr-pages/tldr/commit/df0117359b099af835e8d16c88ff631b7e71f804)

