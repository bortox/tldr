---
author: ['Emily Grace Seville', 'Guido Lena Cota', '85pando', 'bl-ue', 'Seth Falco', 'Ruben Vereecken']
date: 1647882468
title: "xsetwacom"
description: "xsetwacom, Command-line tool to change settings for Wacom pen tablets at runtime."
categories: "linux"
---
> More information: <https://manned.org/xsetwacom>.

- List all the available Wacom devices. The device name is in the first column:

```bash
xsetwacom list
```

- Set Wacom area to specific screen. Get name of the screen with `xrandr`:

```bash
xsetwacom set "device_name" MapToOutput screen
```

- Set mode to relative (like a mouse) or absolute (like a pen) mode:

```bash
xsetwacom set "device_name" Mode "Relative|Absolute"
```

- Rotate the input (useful for tablet-PC when rotating screen) by 0|90|180|270 degrees from "natural" rotation:

```bash
xsetwacom set "device_name" Rotate none|half|cw|ccw
```

- Set button to only work when the tip of the pen is touching the tablet:

```bash
xsetwacom set "device_name" TabletPCButton "on"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[85pando](mailto:85pando@googlemail.com) | Fix typo for xsetwacom. | 2015-11-21T15:53:20 | [0052f1878490](https://github.com/tldr-pages/tldr/commit/0052f1878490674d2f03b9cd7956acb0e286d115)
[85pando](mailto:85pando@users.noreply.github.com) | Improve description | 2015-11-21T12:19:12 | [0cb43407fd82](https://github.com/tldr-pages/tldr/commit/0cb43407fd829ed117c5db9a655d48a1fb9b3499)
[85pando](mailto:85pando@users.noreply.github.com) | Update xsetwacom.md | 2015-11-21T12:16:33 | [75889580d161](https://github.com/tldr-pages/tldr/commit/75889580d1610f2ce2f3cfe69202311fd951df9f)
[85pando](mailto:85pando@users.noreply.github.com) | Fix spelling | 2015-11-21T12:14:25 | [88fcfb906ddf](https://github.com/tldr-pages/tldr/commit/88fcfb906ddf41855d3bd6da67c7e80f778297e0)
[85pando](mailto:85pando@googlemail.com) | Add xsetwacom Xsetwacom is a cli tool to changes settings for Wacom Pen-Tablets. | 2015-11-21T11:54:19 | [69e40dfe3dc6](https://github.com/tldr-pages/tldr/commit/69e40dfe3dc6100f7a56e507e2f5f4ba7225b702)

