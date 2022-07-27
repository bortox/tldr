---
author: ['marchersimon']
date: 1636853331
title: "blurlock, TLDR Pages"
description: "blurlock, A simple wrapper around the i3 screen locker `i3lock`, which blurs the screen."
categories: "linux"
---
> See also: `i3lock`.

> More information: <https://gitlab.manjaro.org/packages/community/i3/i3exit/-/blob/master/blurlock>.

- Lock the screen to a blurred screenshot of the current screen:

```bash
blurlock
```

- Lock the screen and disable the unlock indicator (removes feedback on keypress):

```bash
blurlock --no-unlock-indicator
```

- Lock the screen and don't hide the mouse pointer:

```bash
blurlock --pointer default
```

- Lock the screen and show the number of failed login attempts:

```bash
blurlock --show-failed-attempts
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | blurlock: add page, i3lock: refresh (#7399) | 2021-11-14T02:28:51 | [c5b52b9b8ce3](https://github.com/tldr-pages/tldr/commit/c5b52b9b8ce3e1796a4050a9d7ddd8d3fe72ba05)

