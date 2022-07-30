---
author: ['pxgamer', 'David']
date: 1559676580
title: "noti"
description: "noti, Monitor a process and trigger a banner notification."
categories: "common"
---
> More information: <https://github.com/variadico/noti>.

- Display a notification when tar finishes compressing files:

```bash
noti tar -cjf example.tar.bz2 example/
```

- Display a notification even when you put it after the command to watch:

```bash
command_to_watch; noti
```

- Monitor a process by PID and trigger a notification when the PID disappears:

```bash
noti -w process_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | noti: add link to homepage | 2019-06-04T21:29:40 | [c846b0b0f68f](https://github.com/tldr-pages/tldr/commit/c846b0b0f68fddcedbaabb4e50e5570276d19506)
[David](mailto:david.bialik@gmail.com) | noti: add page (#2544) | 2018-11-05T23:40:08 | [9be2ef777346](https://github.com/tldr-pages/tldr/commit/9be2ef77734677381b6e8486339ae5698eb3d0e8)

