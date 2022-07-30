---
author: ['Jeroen Meulemeester', 'Anna', 'nav1s', 'marchersimon', 'Ruben Vereecken']
date: 1636390112
title: "xrandr"
description: "xrandr, Set the size, orientation and/or reflection of the outputs for a screen."
categories: "linux"
---
> More information: <https://www.x.org/releases/current/doc/man/man1/xrandr.1.xhtml>.

- Display the current state of the system (known screens, resolutions, ...):

```bash
xrandr --query
```

- Disable disconnected outputs and enable connected ones with default settings:

```bash
xrandr --auto
```

- Change the resolution and update frequency of DisplayPort 1 to 1920x1080, 60Hz:

```bash
xrandr --output DP1 --mode 1920x1080 --rate 60
```

- Set the resolution of HDMI2 to 1280x1024 and put it on the right of DP1:

```bash
xrandr --output HDMI2 --mode 1280x1024 --right-of DP1
```

- Disable the VGA1 output:

```bash
xrandr --output VGA1 --off
```

- Set the brightness for LVDS1 to 50%:

```bash
xrandr --output LVDS1 --brightness 0.5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xrandr: remove duplicate example (#7389) | 2021-11-08T17:48:32 | [8793761d559f](https://github.com/tldr-pages/tldr/commit/8793761d559fedf3cb9f1a58705cbd044cba4cde)
[nav1s](mailto:42621369+nav1s@users.noreply.github.com) | xrandr: add more information url (#6920) | 2021-10-09T22:56:21 | [760db1427d4a](https://github.com/tldr-pages/tldr/commit/760db1427d4ab4f338999a0c80829bd6f20f3d26)
[Anna](mailto:33095074+annashorthead@users.noreply.github.com) | xrandr: add brightness and q examples (#4417) | 2020-10-03T04:33:51 | [e4980a21915c](https://github.com/tldr-pages/tldr/commit/e4980a21915cb6e7b31318dbe6ac94973e7f2bba)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | xrandr: add page | 2015-12-31T13:24:15 | [b63075e51f82](https://github.com/tldr-pages/tldr/commit/b63075e51f8254a684ae61eb650b06a242ae3e1f)

