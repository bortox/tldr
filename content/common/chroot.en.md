---
author: ['sebastientinel', 'Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "chroot"
description: "chroot, Run command or interactive shell with special root directory."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/chroot>.

- Run command as new root directory:

```bash
chroot path/to/new/root command
```

- Specify user and group (ID or name) to use:

```bash
chroot --userspec=user:group
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chroot: add more information link (#5602) | 2021-03-30T15:50:36 | [b8f38025f36c](https://github.com/tldr-pages/tldr/commit/b8f38025f36c58be3d109949f4badf9e062b43e0)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

