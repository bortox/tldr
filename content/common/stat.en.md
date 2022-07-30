---
author: ['Sarah Haïm-Lubczanski', 'Felix Yan']
date: 1636014811
title: "stat"
description: "stat, Display file and filesystem information."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/stat-invocation.html>.

- Show file properties such as size, permissions, creation and access dates among others:

```bash
stat file
```

- Same as above but in a more concise way:

```bash
stat -t file
```

- Show filesystem information:

```bash
stat -f file
```

- Show only octal file permissions:

```bash
stat -c "%a %n" file
```

- Show owner and group of the file:

```bash
stat -c "%U %G" file
```

- Show the size of the file in bytes:

```bash
stat -c "%s %n" file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | stat: add more information link (#7302) | 2021-11-04T09:33:31 | [dd56915581a3](https://github.com/tldr-pages/tldr/commit/dd56915581a346ca33304eee108bb5e153d03a62)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

