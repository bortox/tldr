---
author: ['Mirko Conti']
date: 1618868451
title: "sfill, TLDR Pages"
description: "sfill, Securely overwrite the free space and inodes of the partition where the specified directory resides."
categories: "linux"
---
> More information: <https://manned.org/sfill>.

- Overwrite free space and inodes of a disk with 38 writes (slow but secure):

```bash
sfill /path/to/mounted_disk_directory
```

- Overwrite free space and inodes of a disk with 6 writes (fast but less secure) and show status:

```bash
sfill -l -v /path/to/mounted_disk_directory
```

- Overwrite free space and inodes of a disk with 1 write (very fast but insecure) and show status:

```bash
sfill -ll -v /path/to/mounted_disk_directory
```

- Overwrite only free space of a disk:

```bash
sfill -I /path/to/mounted_disk_directory
```

- Overwrite only free inodes of a disk:

```bash
sfill -i /path/to/mounted_disk_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mirko Conti](mailto:mkcn@users.noreply.github.com) | sfill: add page (#5745) | 2021-04-19T23:40:51 | [228e3cc92e45](https://github.com/tldr-pages/tldr/commit/228e3cc92e45e21b921c3459040f57ff767b6a3b)

