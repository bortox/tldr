---
author: ['Stig124', 'Lucas Gabriel Schneider', 'Alone']
date: 1625841955
title: "dmenu"
description: "dmenu, Dynamic menu."
categories: "linux"
---
> Creates a menu from a text input with each item on a new line.

> More information: <https://manned.org/dmenu>.

- Display a menu of the output of the `ls` command:

```bash
ls | dmenu
```

- Display a menu with custom items separated by a new line (`\n`):

```bash
echo -e "red\ngreen\nblue" | dmenu
```

- Let the user choose between multiple items and save the selected one to a file:

```bash
echo -e "red\ngreen\nblue" | dmenu > color.txt
```

- Launch dmenu on a specific monitor:

```bash
ls | dmenu -m 1
```

- Display dmenu at the bottom of the screen:

```bash
ls | dmenu -b
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | dmenu: fix typo (#3742) | 2020-01-09T04:11:10 | [fdac5f1b850c](https://github.com/tldr-pages/tldr/commit/fdac5f1b850c740ff782adc88a2d8e9b0d08dae9)
[Alone](mailto:alain.sinzig@gmail.com) | dmenu: add page (#3474) | 2019-10-28T21:30:04 | [4a37a5b06791](https://github.com/tldr-pages/tldr/commit/4a37a5b06791f0710f8e93cc6142f05bb2386b50)

