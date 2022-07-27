---
author: ['Stig124', 'Amit Sharma']
date: 1625841955
title: "e2fsck, TLDR Pages"
description: "e2fsck, Check a Linux ext2/ext3/ext4 filesystem. The filesystem should be unmounted at the time the command is run."
categories: "linux"
---
> More information: <https://manned.org/e2fsck>.

- Check filesystem, reporting any damaged blocks:

```bash
e2fsck /dev/sdXN
```

- Check filesystem and automatically repair any damaged blocks:

```bash
e2fsck -p /dev/sdXN
```

- Check filesystem in read only mode:

```bash
e2fsck -c /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Amit Sharma](mailto:amitsharma928@gmail.com) | e2fsck: add page (#4438) | 2020-10-05T16:22:57 | [f4a38dbd7e11](https://github.com/tldr-pages/tldr/commit/f4a38dbd7e11081a07c42b9e304aa9816a5b521a)

