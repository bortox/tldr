---
author: ['Sahil Dhiman', 'Reinhart Previano K']
date: 1603894783
title: "scrcpy"
description: "scrcpy, Display and control your Android device on a desktop."
categories: "common"
---
> More information: <https://github.com/Genymobile/scrcpy>.

- Display a mirror of a connected device:

```bash
scrcpy
```

- Display a mirror of a specific device based on its ID or IP address (find it under the `adb devices` command):

```bash
scrcpy --serial 0123456789abcdef|192.168.0.1:5555
```

- Start display in fullscreen mode:

```bash
scrcpy --fullscreen
```

- Rotate the display screen. Each incremental value adds a 90 degree counterclockwise rotation:

```bash
scrcpy --rotation 0|1|2|3
```

- Show touches on physical device:

```bash
scrcpy --show-touches
```

- Record display screen:

```bash
scrcpy --record path/to/file.mp4
```

- Set target directory for pushing files to device by drag and drop (non-APK):

```bash
scrcpy --push-target path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano K](mailto:reinhart_previano@yahoo.com) | scrcpy: add --serial example (#4877) | 2020-10-28T15:19:43 | [dc1f53f8dd61](https://github.com/tldr-pages/tldr/commit/dc1f53f8dd61950fd4e565029223b47b2ecd0bc3)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | scrcpy: add page (#4511) | 2020-10-07T22:29:43 | [772cd9136e8f](https://github.com/tldr-pages/tldr/commit/772cd9136e8f583c462b25f222b3a7295efc76f4)

