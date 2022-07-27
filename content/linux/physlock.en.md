---
author: ['Hannu Hartikainen']
date: 1602714287
title: "physlock, TLDR Pages"
description: "physlock, Lock all consoles and virtual terminals."
categories: "linux"
---
> More information: <http://github.com/muennich/physlock>.

- Lock every console (require current user or root to unlock):

```bash
physlock
```

- Mute kernel messages on console while locked:

```bash
physlock -m
```

- Disable SysRq mechanism while locked:

```bash
physlock -s
```

- Display a message before the password prompt:

```bash
physlock -p "Locked!"
```

- Fork and detach physlock (useful for suspend or hibernate scripts):

```bash
physlock -d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Hannu Hartikainen](mailto:hannu.hartikainen@gmail.com) | physlock: add page (#4682) | 2020-10-15T00:24:47 | [2bf0eb0ed049](https://github.com/tldr-pages/tldr/commit/2bf0eb0ed049399946ca14a7f87b5124907aad06)

