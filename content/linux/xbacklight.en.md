---
author: ['Lawrence Steele']
date: 1568967080
title: "xbacklight"
description: "xbacklight, Utility to adjust backlight brightness using the RandR extension."
categories: "linux"
---
> More information: <https://gitlab.freedesktop.org/xorg/app/xbacklight>.

- Get the current screen brightness as a percentage:

```bash
xbacklight
```

- Set the screen brightness to 40%:

```bash
xbacklight -set 40
```

- Increase current brightness by 25%:

```bash
xbacklight -inc 25
```

- Decrease current brightness by 75%:

```bash
xbacklight -dec 75
```

- Increase backlight to 100%, over 60 seconds (value given in ms), using 60 steps:

```bash
xbacklight -set 100 -time 60000 -steps 60
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lawrence Steele](mailto:larrysteele117@gmail.com) | xbacklight: add page (#3273) | 2019-09-20T10:11:20 | [24f79fe2332c](https://github.com/tldr-pages/tldr/commit/24f79fe2332cab38108a4340ce627ac70cc9a6ce)

