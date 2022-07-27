---
author: ['rozie']
date: 1637874117
title: "wajig, TLDR Pages"
description: "wajig, Simplified all-in-one-place system support tool for Debian-based systems."
categories: "linux"
---
> More information: <https://wajig.togaware.com>.

- Update the list of available packages and versions:

```bash
wajig update
```

- Install a package, or update it to the latest available version:

```bash
wajig install package
```

- Remove a package and its configuration files:

```bash
wajig purge package
```

- Perform an update and then a dist-upgrade:

```bash
wajig daily-upgrade
```

- Display the sizes of installed packages:

```bash
wajig sizes
```

- List the version and distribution for all installed packages:

```bash
wajig versions
```

- List versions of upgradable packages:

```bash
wajig toupgrade
```

- Display packages which have some form of dependency on the given package:

```bash
wajig dependents package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[rozie](mailto:rozie@poczta.onet.pl) | wajig: add page (#7015) | 2021-11-25T22:01:57 | [7fed8f6837bb](https://github.com/tldr-pages/tldr/commit/7fed8f6837bb4b79d3be0586fc97aaf37f9da50f)

