---
author: ['Stig124', 'Amit Sharma']
date: 1625841955
title: "debugfs"
description: "debugfs, An interactive ext2/ext3/ext4 filesystem debugger."
categories: "linux"
---
> More information: <https://manned.org/debugfs>.

- Open the filesystem in read only mode:

```bash
debugfs /dev/sdXN
```

- Open the filesystem in read write mode:

```bash
debugfs -w /dev/sdXN
```

- Read commands from a specified file, execute them and then exit:

```bash
debugfs -f path/to/cmd_file /dev/sdXN
```

- View the filesystem stats in debugfs console:

```bash
stats
```

- Close the filesystem:

```bash
close -a
```

- List all available commands:

```bash
lr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Amit Sharma](mailto:amitsharma928@gmail.com) | debugfs: add page (#4409) | 2020-10-10T01:21:54 | [1659ff508bd4](https://github.com/tldr-pages/tldr/commit/1659ff508bd450ea1d965f0695bdb8db9f2f4d46)

