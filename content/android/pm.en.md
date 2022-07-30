---
author: ['marchersimon']
date: 1616633445
title: "pm"
description: "pm, Show information about apps on an Android device."
categories: "android"
---
> More information: <https://developer.android.com/studio/command-line/adb#pm>.

- Print a list of all installed apps:

```bash
pm list packages
```

- Print a list of all installed system apps:

```bash
pm list packages -s
```

- Print a list of all installed 3rd-Party apps:

```bash
pm list packages -3
```

- Print a list of apps matching specific keywords:

```bash
pm list packages keywords
```

- Print the path of the APK of a specific app:

```bash
pm path app
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/pm: add page (#5458) It's time for another new platform :D :tada: | 2021-03-25T01:50:45 | [c1fb61cf250f](https://github.com/tldr-pages/tldr/commit/c1fb61cf250fc794a45a2e66d7300710e9467d90)

