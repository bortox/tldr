---
author: ['Felix Stein', 'Emily Grace Seville']
date: 1644837703
title: "opensnoop"
description: "opensnoop, Tool that tracks file opens on your system."
categories: "osx"
---
> More information: <https://ss64.com/osx/opensnoop.html>.

- Print all file opens as they occur:

```bash
sudo opensnoop
```

- Track all file opens by a process by name:

```bash
sudo opensnoop -n "process_name"
```

- Track all file opens by a process by PID:

```bash
sudo opensnoop -p PID
```

- Track which processes open a specified file:

```bash
sudo opensnoop -f path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Felix Stein](mailto:flxn@users.noreply.github.com) | opensnoop: add page (#1576) | 2017-10-27T06:03:43 | [aa405d2f20f8](https://github.com/tldr-pages/tldr/commit/aa405d2f20f8f0fd67767200c414d934e2c41790)

