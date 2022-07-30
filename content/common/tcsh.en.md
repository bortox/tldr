---
author: ['Emily Grace Seville']
date: 1656627662
title: "tcsh"
description: "tcsh, C shell with file name completion and command line editing."
categories: "common"
---
> See also: `csh`.

> More information: <https://manned.org/tcsh>.

- Start an interactive shell session:

```bash
tcsh
```

- Start an interactive shell session without loading startup configs:

```bash
tcsh -f
```

- Execute specific [c]ommands:

```bash
tcsh -c "echo 'tcsh is executed'"
```

- Execute a specific script:

```bash
tcsh path/to/script.tcsh
```

- Check a specific script for syntax errors:

```bash
tcsh -n path/to/script.tcsh
```

- Execute specific commands from stdin:

```bash
echo "echo 'tcsh is executed'" | tcsh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tcsh: refresh page (#7985) | 2022-07-01T00:21:02 | [df0ad135f9ce](https://github.com/tldr-pages/tldr/commit/df0ad135f9ce17623236f47344372dacebff87ea)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tcsh: add page (#7421) | 2021-11-14T20:35:13 | [2fffd9d6a173](https://github.com/tldr-pages/tldr/commit/2fffd9d6a173347901c015eae590a8e03e16bc38)

