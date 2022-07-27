---
author: ['Pierre Rudloff', 'Axel Navarro']
date: 1642131234
title: "check-language-support, TLDR Pages"
description: "check-language-support, Display a list of missing language packages on Ubuntu."
categories: "linux"
---
> More information: <https://manpages.ubuntu.com/manpages/latest/man1/check-language-support.html>.

- Display a list of missing language packages based on installed software and enabled locales:

```bash
check-language-support
```

- List packages for a specific locale:

```bash
check-language-support --language en
```

- Display installed packages as well as missing ones:

```bash
check-language-support --show-installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | check-language-support, faketime, pi, powerstat, rig, xdg-user-dirs-update: update links (#7644) | 2022-01-14T04:33:54 | [d5cfac8d3581](https://github.com/tldr-pages/tldr/commit/d5cfac8d3581cf0f9d735fbcefe9bf3b02815441)
[Pierre Rudloff](mailto:contact@rudloff.pro) | check-language-support: add page (#6919) | 2021-10-12T05:00:57 | [d050330c07c9](https://github.com/tldr-pages/tldr/commit/d050330c07c995bdf2291be99e89ed9f86cb2433)

