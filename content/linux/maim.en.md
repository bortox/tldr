---
author: ['IDF']
date: 1603906215
title: "maim"
description: "maim, Screenshot utility."
categories: "linux"
---
> More information: <https://github.com/naelstrof/maim>.

- Capture a screenshot and save it to the given path:

```bash
maim path/to/screenshot.png
```

- Capture a screenshot of the selected region:

```bash
maim --select path/to/screenshot.png
```

- Capture a screenshot of the selected region and save it in the clipboard (requires `xclip`):

```bash
maim --select | xclip -selection clipboard -target image/png
```

- Capture a screenshot of the current active window (requires `xdotool`):

```bash
maim --window $(xdotool getactivewindow) path/to/screenshot.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[IDF](mailto:idf31@protonmail.com) | maim: add page (#4468) | 2020-10-28T18:30:15 | [b0548ef94bd0](https://github.com/tldr-pages/tldr/commit/b0548ef94bd0bbd730bc1990b4d9e7589d8d937b)

