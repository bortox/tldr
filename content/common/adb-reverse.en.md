---
author: ['Axel Navarro']
date: 1598829463
title: "adb reverse"
description: "adb reverse, Android Debug Bridge Reverse: reverse socket connections from an Android emulator instance or connected Android devices."
categories: "common"
---
> More information: <https://developer.android.com/studio/command-line/adb>.

- List all reverse socket connections from emulators and devices:

```bash
adb reverse --list
```

- Reverse a TCP port from an emulator or device to localhost:

```bash
adb reverse tcp:remote_port tcp:local_port
```

- Remove a reverse socket connections from an emulator or device:

```bash
adb reverse --remove tcp:remote_port
```

- Remove all reverse socket connections from all emulators and devices:

```bash
adb reverse --remove-all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | adb-reverse: add page (#4288) | 2020-08-31T01:17:43 | [cb2073c4ff81](https://github.com/tldr-pages/tldr/commit/cb2073c4ff81cbf7351465d13898605de35013e1)

