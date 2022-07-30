---
author: ['Lachlan Marnham', 'Emily Grace Seville']
date: 1647882468
title: "vncviewer"
description: "vncviewer, Launches a VNC (Virtual Network Computing) client."
categories: "linux"
---
> More information: <https://manned.org/vncviewer>.

- Launch a VNC client which connects to a host on a given display:

```bash
vncviewer host:display_number
```

- Launch in full-screen mode:

```bash
vncviewer -FullScreen host:display_number
```

- Launch a VNC client with a specific screen geometry:

```bash
vncviewer --geometry widthxheight host:display_number
```

- Launch a VNC client which connects to a host on a given port:

```bash
vncviewer host::port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Lachlan Marnham](mailto:lachlan.marnham@gmail.com) | vncviewer: add page (#2401) | 2018-10-09T00:06:44 | [a777ea5d896e](https://github.com/tldr-pages/tldr/commit/a777ea5d896e73fa266674f514c48ce6159a3171)

