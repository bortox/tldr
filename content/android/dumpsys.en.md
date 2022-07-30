---
author: ['marchersimon']
date: 1619122161
title: "dumpsys"
description: "dumpsys, Provide information about Android system services."
categories: "android"
---
> This command can only be used through `adb shell`.

> More information: <https://developer.android.com/studio/command-line/dumpsys>.

- Get diagnostic output for all system services:

```bash
dumpsys
```

- Get diagnostic output for a specific system service:

```bash
dumpsys service
```

- List all services `dumpsys` can give information about:

```bash
dumpsys -l
```

- List service-specific arguments for a service:

```bash
dumpsys service -h
```

- Exclude a specific service from the diagnostic output:

```bash
dumpsys --skip service
```

- Specify a timeout period in seconds (defaults to 10s):

```bash
dumpsys -t seconds
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: fix command descriptions (#5807) | 2021-04-22T22:09:21 | [4b891616c6a1](https://github.com/tldr-pages/tldr/commit/4b891616c6a1f21e836b56d216b7ec008e1dd746)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dumpsys: add page (#5739) | 2021-04-14T22:21:59 | [de637c416d65](https://github.com/tldr-pages/tldr/commit/de637c416d65d4b849e01677caad1faea3e435bc)

