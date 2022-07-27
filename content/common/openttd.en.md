---
author: ['Florian B']
date: 1618577700
title: "openttd, TLDR Pages"
description: "openttd, Open source clone of the Microprose game 'Transport Tycoon Deluxe'."
categories: "common"
---
> More information: <https://www.openttd.org>.

- Start a new game:

```bash
openttd -g
```

- Load save game at start:

```bash
openttd -g path/to/file
```

- Start with the specified window resolution:

```bash
openttd -r 1920x1080
```

- Start with a custom configuration file:

```bash
openttd -c path/to/file
```

- Start with selected video, sound, and music drivers:

```bash
openttd -v video_driver -s sound_driver -m music_driver
```

- Start a dedicated server, forked in the background:

```bash
openttd -f -D host:port
```

- Join a server with a password:

```bash
openttd -n host:port#player_name -p password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:florian.benscheidt@ogd.nl) | openttd: add page (#5765) | 2021-04-16T14:55:00 | [97f9d86ae037](https://github.com/tldr-pages/tldr/commit/97f9d86ae037ffe110d2be82e1168c8b547bfff4)

