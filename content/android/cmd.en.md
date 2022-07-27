---
author: ['Pierre Rudloff', 'marchersimon']
date: 1617135948
title: "cmd, TLDR Pages"
description: "cmd, Android service manager."
categories: "android"
---
> More information: <https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/cmd/>.

- List every running service:

```bash
cmd -l
```

- Call a specific service:

```bash
cmd alarm
```

- Call a service with arguments:

```bash
cmd vibrator vibrate 300
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cmd: add more information link (#5581) | 2021-03-30T22:25:48 | [8e35e5eebc98](https://github.com/tldr-pages/tldr/commit/8e35e5eebc98b96f4adf23d24052f30279e3e867)
[Pierre Rudloff](mailto:contact@rudloff.pro) | am, cmd, dalvikvm, settings: add page (#5481) | 2021-03-25T22:57:15 | [59ca98f7df99](https://github.com/tldr-pages/tldr/commit/59ca98f7df994e7642d21691cfe80e478c67bf3a)

