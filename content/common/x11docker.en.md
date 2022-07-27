---
author: ['Axel Navarro']
date: 1619539774
title: "x11docker, TLDR Pages"
description: "x11docker, Securely run GUI applications and desktop UIs in Docker containers."
categories: "common"
---
> See also `xephyr`.

> More information: <https://github.com/mviereck/x11docker>.

- Launch VLC in a container:

```bash
x11docker --pulseaudio --share=$HOME/Videos jess/vlc
```

- Launch Xfce in a window:

```bash
x11docker --desktop x11docker/xfce
```

- Launch GNOME in a window:

```bash
x11docker --desktop --gpu --init=systemd x11docker/gnome
```

- Launch KDE Plasma in a window:

```bash
x11docker --desktop --gpu --init=systemd x11docker/kde-plasma
```

- Display help:

```bash
x11docker --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | x11docker: add page (#5835) * x11docker: add page * Update pages/common/x11docker.md * Update pages/common/x11docker.md Co-authored- [...] | 2021-04-27T18:09:34 | [71c0279659c1](https://github.com/tldr-pages/tldr/commit/71c0279659c1ec1d7e161cb4751fe091058917ae)

