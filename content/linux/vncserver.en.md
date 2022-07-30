---
author: ['Jeef', 'Emily Grace Seville']
date: 1647882468
title: "vncserver"
description: "vncserver, Launches a VNC (Virtual Network Computing) desktop."
categories: "linux"
---
> More information: <https://manned.org/vncserver.1x>.

- Launch a VNC Server on next available display:

```bash
vncserver
```

- Launch a VNC Server with specific screen geometry:

```bash
vncserver --geometry widthxheight
```

- Kill an instance of VNC Server running on a specific display:

```bash
vncserver --kill :display_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Jeef](mailto:jeeftor@users.noreply.github.com) | vncserver: Add page (#1290) | 2017-03-10T05:50:47 | [d5f77158791a](https://github.com/tldr-pages/tldr/commit/d5f77158791a817b1c171299256ecc6e86e6d60f)

