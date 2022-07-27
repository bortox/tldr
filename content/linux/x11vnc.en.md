---
author: ['Waldir Pimenta', 'Jeef', 'bl-ue', 'Emily Grace Seville']
date: 1647882468
title: "x11vnc, TLDR Pages"
description: "x11vnc, A VNC server that will enable VNC on an existing display server."
categories: "linux"
---
> By default, the server will automatically terminate once all clients disconnect from it.

> More information: <https://manned.org/x11vnc>.

- Launch a VNC server that allows multiple clients to connect:

```bash
x11vnc -shared
```

- Launch a VNC server in view-only mode, and which won't terminate once the last client disconnects:

```bash
x11vnc -forever -viewonly
```

- Launch a VNC server on a specific display and screen (both starting at index zero):

```bash
x11vnc -display :display.screen
```

- Launch a VNC server on the third display's default screen:

```bash
x11vnc -display :2
```

- Launch a VNC server on the first display's second screen:

```bash
x11vnc -display :0.1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | x11vnc: wording tweaks (#1324) * x11vnc: wording tweaks * x11vnc: clarify monitor vs. display vs. screen See [...] | 2017-04-18T15:04:53 | [c644c19a8c42](https://github.com/tldr-pages/tldr/commit/c644c19a8c42c98f28bed297698e5f6c68931623)
[Jeef](mailto:jeeftor@users.noreply.github.com) | x11vnc, xdotool, rev: add pages (#1264) | 2017-02-21T04:52:56 | [8fdc908325c5](https://github.com/tldr-pages/tldr/commit/8fdc908325c52c333fc3652a3afd38a54cff21b7)

