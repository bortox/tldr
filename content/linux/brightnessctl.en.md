---
author: ['DaxGoon', 'Maksim Verkhoturov']
date: 1657894274
title: "brightnessctl"
description: "brightnessctl, Utility for reading and controlling device brightness for GNU/Linux operating systems."
categories: "linux"
---
> More information: <https://github.com/Hummer12007/brightnessctl>.

- List devices with changeable brightness:

```bash
brightnessctl --list
```

- Print the current brightness of the display backlight:

```bash
brightnessctl get
```

- Set the brightness of the display backlight to a specified percentage within range:

```bash
brightnessctl set 50%
```

- Increase brightness by a specified increment:

```bash
brightnessctl set +10%
```

- Decrease brightness by a specified decrement:

```bash
brightnessctl set 10%-
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Maksim Verkhoturov](mailto:sd32@protonmail.com) | brightnessctl: fix typo in decrease example (#8213) | 2022-07-15T16:11:14 | [50f543866e0c](https://github.com/tldr-pages/tldr/commit/50f543866e0cbe34d70b19cc1eca4cd53a8f8120)
[DaxGoon](mailto:44712376+DaxGoon@users.noreply.github.com) | brightnessctl: add page (#6516) | 2021-09-16T19:49:58 | [500f96361921](https://github.com/tldr-pages/tldr/commit/500f963619216ef138f0cd45d9050ca871e1c499)

