---
author: ['Stig124', 'newtant']
date: 1625841955
title: "blkid, TLDR Pages"
description: "blkid, Lists all recognized partitions and their Universally Unique Identifier (UUID)."
categories: "linux"
---
> More information: <https://manned.org/blkid>.

- List all partitions:

```bash
sudo blkid
```

- List all partitions in a table, including current mountpoints:

```bash
sudo blkid -o list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[newtant](mailto:newtant@users.noreply.github.com) | blkid: add page (#2957) | 2019-05-01T10:08:01 | [04a427a9e263](https://github.com/tldr-pages/tldr/commit/04a427a9e2631653c079f5ef5ab5c72b3e8690af)

