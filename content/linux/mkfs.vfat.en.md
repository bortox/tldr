---
author: ['85pando', 'Lucas Gabriel Schneider', 'Agniva De Sarker']
date: 1629110041
title: "mkfs.vfat"
description: "mkfs.vfat, Creates an MS-DOS filesystem inside a partition."
categories: "linux"
---
> More information: <https://manned.org/mkfs.vfat>.

- Create a vfat filesystem inside partition 1 on device b (`sdb1`):

```bash
mkfs.vfat /dev/sdb1
```

- Create filesystem with a volume-name:

```bash
mkfs.vfat -n volume_name /dev/sdb1
```

- Create filesystem with a volume-id:

```bash
mkfs.vfat -i volume_id /dev/sdb1
```

- Use 5 instead of 2 file allocation tables:

```bash
mkfs.vfat -f 5 /dev/sdb1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[85pando](mailto:85pando@googlemail.com) | Add several mkfs tools | 2016-01-13T16:50:06 | [7521d8b8930e](https://github.com/tldr-pages/tldr/commit/7521d8b8930e629d0a2d7a9e15b1eab704c2ebc8)

