---
author: ['Lucas Gabriel Schneider', 'Shashank Shekhar']
date: 1629110041
title: "mkswap, TLDR Pages"
description: "mkswap, Sets up a Linux swap area on a device or in a file."
categories: "linux"
---
> More information: <https://manned.org/mkswap>.

- Setup a given partition as swap area:

```bash
sudo mkswap /dev/sdb7
```

- Use a given file as swap area:

```bash
sudo mkswap path/to/file
```

- Check a partition for bad blocks before creating the swap area:

```bash
sudo mkswap -c /dev/sdb7
```

- Specify a label for the file (to allow `swapon` to use the label):

```bash
sudo mkswap -L swap1 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Shashank Shekhar](mailto:correspond.shashank@gmail.com) | mkswap: add page (#1984) | 2018-02-12T23:03:12 | [c67396e6e16b](https://github.com/tldr-pages/tldr/commit/c67396e6e16b231e05bd05b3dbe738f5e3d08175)

