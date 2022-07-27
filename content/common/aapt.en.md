---
author: ['Pierre Rudloff', 'marchersimon']
date: 1613853055
title: "aapt, TLDR Pages"
description: "aapt, Android Asset Packaging Tool."
categories: "common"
---
> Compile and package an Android app's resources.

> More information: <https://elinux.org/Android_aapt>.

- List files contained in an APK archive:

```bash
aapt list path/to/app.apk
```

- Display an app's metadata (version, permissions, etc.):

```bash
aapt dump badging path/to/app.apk
```

- Create a new APK archive with files from the specified directory:

```bash
aapt package -F path/to/app.apk path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)
[Pierre Rudloff](mailto:contact@rudloff.pro) | aapt: add page (#3544) | 2019-11-14T22:44:36 | [c704bd8ec569](https://github.com/tldr-pages/tldr/commit/c704bd8ec569ecdbad3b6199fc9f43739d3e601f)

