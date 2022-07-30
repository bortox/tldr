---
author: ['Jonathan Dahan']
date: 1577710132
title: "tic"
description: "tic, Compile terminfo and install for ncurses."
categories: "linux"
---
> More information: <https://pubs.opengroup.org/onlinepubs/007908799/xcurses/terminfo.html>.

- Compile and install terminfo for a terminal:

```bash
tic -xe terminal path/to/terminal.info
```

- Check terminfo file for errors:

```bash
tic -c path/to/terminal.info
```

- Print database locations:

```bash
tic -D
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonathan Dahan](mailto:hi@jonathan.is) | tic: add page (#3699) | 2019-12-30T13:48:52 | [7ac600865d9d](https://github.com/tldr-pages/tldr/commit/7ac600865d9d0c6a5ef52577a5946bf27ad21ad4)

