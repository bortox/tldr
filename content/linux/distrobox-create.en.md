---
author: ['Mišo Barišić']
date: 1642879685
title: "distrobox-create, TLDR Pages"
description: "distrobox-create, Create Distrobox containers with an input name and image."
categories: "linux"
---
> The created container will be tightly integrated with the host, allowing sharing of the HOME directory of the user, external storage, external usb devices and graphical apps (X11/Wayland), and audio.

> More information: <https://distrobox.privatedns.org>.

- Create a distrobox using the Alpine image:

```bash
distrobox-create container_name --image alpine
```

- Clone a distrobox:

```bash
distrobox-create --clone container_name cloned_container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mišo Barišić](mailto:50531162+misobarisic@users.noreply.github.com) | distrobox: add page (#7638) | 2022-01-22T20:28:05 | [26adab31c663](https://github.com/tldr-pages/tldr/commit/26adab31c66345a0ae5fc2deaf410167cbda10ef)

