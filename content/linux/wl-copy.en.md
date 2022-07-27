---
author: ['Anthony Saldana Valle', 'Oğuz Ersen', 'Emily Grace Seville']
date: 1647721012
title: "wl-copy, TLDR Pages"
description: "wl-copy, Wayland clipboard manipulation tool."
categories: "linux"
---
> See also: `wl-paste`.

> More information: <https://github.com/bugaevc/wl-clipboard>.

- Copy the text to the clipboard:

```bash
wl-copy "text"
```

- Pipe the command (`ls`) output to the clipboard:

```bash
ls | wl-copy
```

- Copy for only one paste and then clear it:

```bash
wl-copy --paste-once "text"
```

- Clear the clipboard:

```bash
wl-copy --clear
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | wl-copy: page update (#7901) | 2022-03-19T21:16:52 | [3202852b03f0](https://github.com/tldr-pages/tldr/commit/3202852b03f0f53c0c9b61466c55656adad9496e)
[Oğuz Ersen](mailto:oguzersen@protonmail.com) | atool, dnf, wl-copy, wl-paste: add Turkish translation (#7837) * wl-copy, wl-paste: fix invalid command options --paste-once is valid [...] | 2022-03-17T06:08:52 | [e7a06bac2805](https://github.com/tldr-pages/tldr/commit/e7a06bac28057862cb80128905031eab5173ff0b)
[Anthony Saldana Valle](mailto:55422282+ansavanix@users.noreply.github.com) | wl-paste: add page, wl-copy: update link (#7123) | 2021-11-14T20:21:15 | [6c600e3df524](https://github.com/tldr-pages/tldr/commit/6c600e3df52446d41e7cc576f3dde016aef611df)
[Anthony Saldana Valle](mailto:55422282+ansavanix@users.noreply.github.com) | wl-copy: add page (#6753) | 2021-10-18T06:36:11 | [24670dd69c3d](https://github.com/tldr-pages/tldr/commit/24670dd69c3d7e23905aea037dbc714342ae6428)

