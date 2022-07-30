---
author: ['Reinhart Previano Koentjoro']
date: 1634662499
title: "cups-config"
description: "cups-config, Show technical information about your CUPS print server installation."
categories: "common"
---
> More information: <https://www.cups.org/doc/man-cups-config.html>.

- Show the currently installed version of CUPS:

```bash
cups-config --version
```

- Show where CUPS is currently installed:

```bash
cups-config --serverbin
```

- Show the location of CUPS' configuration directory:

```bash
cups-config --serverroot
```

- Show the location of CUPS' data directory:

```bash
cups-config --datadir
```

- Display all available options:

```bash
cups-config --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | cups-config, cupsd, lpinfo: add page (#6623) | 2021-10-19T18:54:59 | [79591fecf696](https://github.com/tldr-pages/tldr/commit/79591fecf696bb2c72db053431f3db6f62bf9231)

