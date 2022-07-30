---
author: ['Axel Navarro']
date: 1614292230
title: "kwriteconfig5"
description: "kwriteconfig5, Write KConfig entries for KDE Plasma."
categories: "linux"
---
> More information: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Display help:

```bash
kwriteconfig5 --help
```

- Set a global configuration key:

```bash
kwriteconfig5 --group group_name --key key value
```

- Set a key in a specific configuration file:

```bash
kwriteconfig5 --file path/to/file --group group_name --key key value
```

- Delete a key:

```bash
kwriteconfig5 --group group_name --key key --delete
```

- Use systemd to start the Plasma session when available:

```bash
kwriteconfig5 --file startkderc --group General --key systemdBoot true
```

- Hide the title bar when a window is maximized (like Ubuntu):

```bash
kwriteconfig5 --file ~/.config/kwinrc --group Windows --key BorderlessMaximizedWindows true
```

- Configure KRunner to open with the Meta (Command/Windows) global hotkey:

```bash
kwriteconfig5 --file ~/.config/kwinrc --group ModifierOnlyShortcuts --key Meta "org.kde.kglobalaccel,/component/krunner_desktop,org.kde.kglobalaccel.Component,invokeShortcut,_launch"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | kwriteconfig5: add page (#5292) | 2021-02-25T23:30:30 | [18961bc91eb6](https://github.com/tldr-pages/tldr/commit/18961bc91eb6c6dc9519d20de1af32d59471b734)

