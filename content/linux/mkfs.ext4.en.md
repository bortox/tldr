---
author: ['Michael Lindner', 'Lucas Gabriel Schneider']
date: 1629110041
title: "mkfs.ext4"
description: "mkfs.ext4, Creates an ext4 filesystem inside a partition."
categories: "linux"
---
> More information: <https://manned.org/mkfs.ext4>.

- Create an ext4 filesystem inside partition 1 on device b (`sdb1`):

```bash
sudo mkfs.ext4 /dev/sdb1
```

- Create an ext4 filesystem with a volume-label:

```bash
sudo mkfs.ext4 -L volume_label /dev/sdb1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Michael Lindner](mailto:3502223+MikeLindner@users.noreply.github.com) | mkfs.ext4: add page (#3986) | 2020-04-18T17:27:57 | [1fd81dfadceb](https://github.com/tldr-pages/tldr/commit/1fd81dfadceb0aee34635c0eeaec9f84b52d4c62)

