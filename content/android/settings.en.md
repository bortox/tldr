---
author: ['Pierre Rudloff', 'marchersimon']
date: 1617187708
title: "settings, TLDR Pages"
description: "settings, Get information about the Android OS."
categories: "android"
---
> More information: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Display a list of settings in the `global` namespace:

```bash
settings list global
```

- Get the value of a specific setting:

```bash
settings get global airplane_mode_on
```

- Set the value of a setting:

```bash
settings put system screen_brightness 42
```

- Delete a specific setting:

```bash
settings delete secure screensaver_enabled
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | settings: add more information link (#5530) | 2021-03-31T12:48:28 | [b02c9f5a2548](https://github.com/tldr-pages/tldr/commit/b02c9f5a25488678811c18f53e675f89d3cfca68)
[Pierre Rudloff](mailto:contact@rudloff.pro) | am, cmd, dalvikvm, settings: add page (#5481) | 2021-03-25T22:57:15 | [59ca98f7df99](https://github.com/tldr-pages/tldr/commit/59ca98f7df994e7642d21691cfe80e478c67bf3a)

