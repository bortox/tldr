---
author: ['David Judge', 'syleung']
date: 1633350747
title: "Xephyr"
description: "Xephyr, A nested X server that runs as an X application."
categories: "common"
---
> More information: <https://manned.org/xserver-xephyr>.

- Create a black window with display ID ":2":

```bash
Xephyr -br -ac -noreset -screen 800x600 :2
```

- Start an X application on the new screen:

```bash
DISPLAY=:2 command_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/x*: add more information link (#6664) | 2021-10-04T14:32:27 | [99a72c556f56](https://github.com/tldr-pages/tldr/commit/99a72c556f563a928a10ff2c2146ad42d9af2990)
[David Judge](mailto:dbiro97@gmail.com) | xephyr: add page (#4365) | 2020-09-30T13:16:32 | [fc606a6cb2d6](https://github.com/tldr-pages/tldr/commit/fc606a6cb2d6ab53d6732d600d1a20b5d0a4afbe)

