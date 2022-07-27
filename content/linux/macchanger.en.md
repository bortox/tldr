---
author: ['Quentin', 'Lucas Gabriel Schneider']
date: 1629110041
title: "macchanger, TLDR Pages"
description: "macchanger, Command-line utility for manipulating network interface MAC addresses."
categories: "linux"
---
> More information: <https://manned.org/macchanger>.

- View the current and permanent MAC addresses of a interface:

```bash
macchanger --show interface
```

- Set interface to a random MAC:

```bash
macchanger --random interface
```

- Set interface to a specific MAC:

```bash
macchanger --mac XX:XX:XX:XX:XX:XX interface
```

- Reset interface to its permanent hardware MAC:

```bash
macchanger --permanent interface
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Quentin](mailto:36890802+UserBlackBox@users.noreply.github.com) | macchanger: add page (#4087) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-06-04T15:43:59 | [847f0c209487](https://github.com/tldr-pages/tldr/commit/847f0c209487e624abec4e97a49499327c6fa09f)

