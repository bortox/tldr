---
author: ['pixel']
date: 1631917190
title: "xprop, TLDR Pages"
description: "xprop, A tool for displaying window and font properties in an X server."
categories: "common"
---
> More information: <https://manned.org/xprop>.

- Display the name of the root window:

```bash
xprop -root WM_NAME
```

- Display the window manager hints for a window:

```bash
xprop -name "window_name" WM_HINTS
```

- Display the point size of a font:

```bash
xprop -font "font_name" POINT_SIZE
```

- Display all the properties of the window with the id 0x200007:

```bash
xprop -id 0x200007
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | xprop: add page (#6429) | 2021-09-18T00:19:50 | [34634ad15500](https://github.com/tldr-pages/tldr/commit/34634ad15500889391d288104098e16348e8b5a9)

