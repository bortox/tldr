---
author: ['Morgan Howard']
date: 1634008434
title: "launchd"
description: "launchd, This manages processes, both for the system and users."
categories: "osx"
---
> You cannot invoke launchd manually, use launchctl to interact with it.

> More information: <https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/Introduction.html>.

- Run init:

```bash
/sbin/launchd
```

- View documentation for interacting with launchd using launchctl:

```bash
tldr launchctl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Morgan Howard](mailto:morganhoward@users.noreply.github.com) | osx/*: add page for macOS interal daemons (#6705) appsleepd auditd avbdevided bird bnepd cfprefsd cloudphotod coreaudiod distnoted [...] | 2021-10-12T05:13:54 | [bb83c2b70569](https://github.com/tldr-pages/tldr/commit/bb83c2b705696df0df9a1b1407baf4df0ebd2ffe)

