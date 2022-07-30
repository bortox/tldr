---
author: ['marchersimon']
date: 1618756617
title: "qjoypad"
description: "qjoypad, Translate input from gamepads or joysticks into keyboard strokes or mouse actions."
categories: "linux"
---
> More information: <http://qjoypad.sourceforge.net/>.

- Start QJoyPad:

```bash
qjoypad
```

- Start QJoyPad and look for devices in a specific directory:

```bash
qjoypad --device=path/to/directory
```

- Start QJoyPad but don't show a system tray icon:

```bash
qjoypad --notray
```

- Start QJoyPad and force the window manager to use a system tray icon:

```bash
qjoypad --force-tray
```

- Force a running instance of QJoyPad to update its list of devices and layouts:

```bash
qjoypad --update
```

- Load the given layout in an already running instance of QJoyPad, or start QJoyPad using the given layout:

```bash
qjoypad "layout"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | qjoypad: add page (#5783) * qjoypad: add page * Fix typo Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> * Apply [...] | 2021-04-18T16:36:57 | [0ca6ac1efbaa](https://github.com/tldr-pages/tldr/commit/0ca6ac1efbaa10dc1eb49033a63c12c16c33e07e)

