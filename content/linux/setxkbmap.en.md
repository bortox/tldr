---
author: ['Maartz', 'PrimaMateria', 'Emily Grace Seville']
date: 1647882468
title: "setxkbmap, TLDR Pages"
description: "setxkbmap, Set the keyboard using the X Keyboard Extension."
categories: "linux"
---
> More information: <https://manned.org/setxkbmap>.

- Set the keyboard in French AZERTY:

```bash
setxkbmap fr
```

- Set multiple keyboard layouts, their variants and switching option:

```bash
setxkbmap -layout us,de -variant ,qwerty -option 'grp:alt_caps_toggle'
```

- Get help:

```bash
setxkbmap -help
```

- List all layouts:

```bash
localectl list-x11-keymap-layouts
```

- List variants for the layout:

```bash
localectl list-x11-keymap-variants de
```

- List available switching options:

```bash
localectl list-x11-keymap-options | grep grp:
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[PrimaMateria](mailto:matus.benko@gmail.com) | setxkbmap: add complex example and available values examples (#3353) | 2019-10-11T20:58:42 | [6d5a335b5021](https://github.com/tldr-pages/tldr/commit/6d5a335b5021bf6e01db2cdca418a7408df4f227)
[Maartz](mailto:maartz@protonmail.com) | setxkbmap: add page (#3288) | 2019-10-03T12:23:34 | [f2898e5811af](https://github.com/tldr-pages/tldr/commit/f2898e5811afdda798587404bcc9104eda4d4b7b)

