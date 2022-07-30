---
author: ['ISU', 'asas1asas200', 'user56441']
date: 1640555203
title: "xbps"
description: "xbps, The X Binary Package System (or xbps) is the binary package system used by Void Linux."
categories: "linux"
---
> More information: <https://github.com/void-linux/xbps>.

- Install packages and synchronize them with the remote repository:

```bash
xbps-install --sync package_name1 package_name2
```

- Search for a package in the remote repository:

```bash
xbps-query --repository -s package_name
```

- Remove a package, leaving all of its dependencies installed:

```bash
xbps-remove package_name
```

- Remove a package and all of its dependencies recursively that are not required by other packages:

```bash
xbps-remove --recursive package_name
```

- Synchronize your repository databases and update your system and dependencies:

```bash
xbps-install --sync --update
```

- Remove packages that were installed as dependencies and aren't currently needed:

```bash
xbps-remove --remove-orphans
```

- Remove obsolete packages from the cache:

```bash
xbps-remove --clean-cache
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[asas1asas200](mailto:asas1asas200@gmail.com) | xbps: fix --sync and --update examples (#7574) | 2021-12-26T22:46:43 | [0600ada30d25](https://github.com/tldr-pages/tldr/commit/0600ada30d25630b360954a270878e7476082029)
[user56441](mailto:62631913+user56441@users.noreply.github.com) | xbps: update page (#3936) | 2020-03-28T02:27:33 | [f5026bd6f974](https://github.com/tldr-pages/tldr/commit/f5026bd6f974391ee4e99ba9007606b407b60ffe)
[ISU](mailto:isu17@users.noreply.github.com) | xbps: add page (#2211) | 2018-09-26T15:47:04 | [2763a5f7b732](https://github.com/tldr-pages/tldr/commit/2763a5f7b732eafd4d4a5c98c1838cc8c25d8402)

