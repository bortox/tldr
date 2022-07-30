---
author: ['Lucas Gabriel Schneider', 'Seth Falco', 'Maharaj Fawwaz Almuqaddim Yusran']
date: 1629110041
title: "lsusb"
description: "lsusb, Display information about USB buses and devices connected to them."
categories: "linux"
---
> More information: <https://manned.org/lsusb>.

- List all the USB devices available:

```bash
lsusb
```

- List the USB hierarchy as a tree:

```bash
lsusb -t
```

- List verbose information about USB devices:

```bash
lsusb --verbose
```

- List detailed information about a USB device:

```bash
lsusb -D device
```

- List devices with a specified vendor and product ID only:

```bash
lsusb -d vendor:product
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Maharaj Fawwaz Almuqaddim Yusran](mailto:fawwazyusran@gmail.com) | lsusb: add page (#2409) | 2018-10-09T22:12:30 | [d5ae9f93c43f](https://github.com/tldr-pages/tldr/commit/d5ae9f93c43f71088b15b6c6d2bcd80e399199ac)

