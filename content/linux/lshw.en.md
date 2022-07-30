---
author: ['Lucas Gabriel Schneider', 'Seth Falco', 'Max Xu']
date: 1629110041
title: "lshw"
description: "lshw, List detailed information about hardware configurations as root user."
categories: "linux"
---
> More information: <https://manned.org/lshw>.

- Launch the GUI:

```bash
sudo lshw -X
```

- List all hardware in tabular format:

```bash
sudo lshw -short
```

- List all disks and storage controllers in tabular format:

```bash
sudo lshw -class disk -class storage -short
```

- Save all network interfaces to an HTML file:

```bash
sudo lshw -class network -html > interfaces.html
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Max Xu](mailto:xuhuan@live.cn) | lshw: add page (#1854) | 2018-01-01T17:40:38 | [2a35fd66275f](https://github.com/tldr-pages/tldr/commit/2a35fd66275f0605cee90e598bc60f6e100793a2)

