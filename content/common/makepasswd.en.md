---
author: ['Pierre Rudloff']
date: 1573768970
title: "makepasswd, TLDR Pages"
description: "makepasswd, Generate and encrypt passwords."
categories: "common"
---
> More information: <https://manpages.debian.org/stretch/makepasswd/makepasswd.1.en.html>.

- Generate a random password (8 to 10 characters long, containing letters and numbers):

```bash
makepasswd
```

- Generate a 10 characters long password:

```bash
makepasswd --chars 10
```

- Generate a 5 to 10 characters long password:

```bash
makepasswd --minchars 5 --maxchars 10
```

- Generate a password containing only the characters "b", "a" or "r":

```bash
makepasswd --string bar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | makepasswd: add page (#3566) | 2019-11-14T23:02:50 | [f62c41c1b462](https://github.com/tldr-pages/tldr/commit/f62c41c1b462c4115559162250588c610a8203f8)

