---
author: ['enes4949', 'Max Strübing']
date: 1588277085
title: "playerctl"
description: "playerctl, Utility to control different media players."
categories: "linux"
---
> More information: <https://github.com/altdesktop/playerctl>.

- Toggle play:

```bash
playerctl play-pause
```

- Next media:

```bash
playerctl next
```

- Previous media:

```bash
playerctl previous
```

- List all players:

```bash
playerctl --list-all
```

- Send a command to a specific player:

```bash
playerctl --player=player_name command
```

- Send a command to all players:

```bash
playerctl --all-players command
```

- Show now playing:

```bash
playerctl metadata --format "Now playing: artist - album - title"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[enes4949](mailto:63241739+enes4949@users.noreply.github.com) | betterlockscreen : added page (#3972) | 2020-04-30T22:04:45 | [b9a5b0f6d0c1](https://github.com/tldr-pages/tldr/commit/b9a5b0f6d0c1588d98d9d41d639f1cb2bfd721c0)
[enes4949](mailto:63241739+enes4949@users.noreply.github.com) | playerctl: added show now playing (#3967) | 2020-04-07T03:24:51 | [998e0f5f4f5e](https://github.com/tldr-pages/tldr/commit/998e0f5f4f5e605fee54779bb31f75f9ec72ab52)
[Max Strübing](mailto:mxstrbng@gmail.com) | playerctl: add page (#1997) | 2018-02-14T21:14:25 | [a86907d8c4a7](https://github.com/tldr-pages/tldr/commit/a86907d8c4a7e2a6e52f2beea03ac4b60dd20c70)

