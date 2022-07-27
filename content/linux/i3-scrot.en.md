---
author: ['marchersimon']
date: 1638110002
title: "i3-scrot, TLDR Pages"
description: "i3-scrot, Wrapper script around the screenshot utility `scrot` for the i3 window manager."
categories: "linux"
---
> The default save location is `~/Pictures` and can be changed in `~/.config/i3-scrot.conf`.

> More information: <https://gitlab.manjaro.org/packages/community/i3/i3-scrot>.

- Capture a screenshot of the whole screen and save it to the default directory:

```bash
i3-scrot
```

- Capture a screenshot of the active window:

```bash
i3-scrot --window
```

- Capture a screenshot of a specific rectangular selection:

```bash
i3-scrot --select
```

- Capture a screenshot of the whole screen and copy it to the clipboard:

```bash
i3-scrot --desk-to-clipboard
```

- Capture a screenshot of the active window and copy it to the clipboard:

```bash
i3-scrot --window-to-clipboard
```

- Capture a screenshot of a specific selection and copy it to the clipboard:

```bash
i3-scrot --select-to-clibpoard
```

- Capture a screenshot of the active window after a delay of 5 seconds:

```bash
i3-scrot --window 5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | i3-scrot: add page (#7400) | 2021-11-28T15:33:22 | [cc61950686f4](https://github.com/tldr-pages/tldr/commit/cc61950686f4cd7617f4999e6500c1275f10abe3)

