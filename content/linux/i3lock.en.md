---
author: ['jvktr', 'Seth Falco', 'marchersimon']
date: 1636853331
title: "i3lock, TLDR Pages"
description: "i3lock, Simple screen locker built for the i3 window manager."
categories: "linux"
---
> More information: <https://i3wm.org/i3lock>.

- Lock the screen showing a white background:

```bash
i3lock
```

- Lock the screen with a simple color background (rrggbb format):

```bash
i3lock --color 0000ff
```

- Lock the screen to a PNG background:

```bash
i3lock --image path/to/file.png
```

- Lock the screen and disable the unlock indicator (removes feedback on keypress):

```bash
i3lock --no-unlock-indicator
```

- Lock the screen and don't hide the mouse pointer:

```bash
i3lock --pointer default
```

- Lock the screen to a PNG background tiled over all monitors:

```bash
i3lock --image path/to/file.png --tiling
```

- Lock the screen and show the number of failed login attempts:

```bash
i3lock --show-failed-attempts
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | blurlock: add page, i3lock: refresh (#7399) | 2021-11-14T02:28:51 | [c5b52b9b8ce3](https://github.com/tldr-pages/tldr/commit/c5b52b9b8ce3e1796a4050a9d7ddd8d3fe72ba05)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[jvktr](mailto:67814222+jvktr@users.noreply.github.com) | i3lock: add page (EN/pt_BR) (#4146) | 2020-07-05T22:54:09 | [07d98683896d](https://github.com/tldr-pages/tldr/commit/07d98683896deca8ca65c49ac7dd3cb506302c02)

