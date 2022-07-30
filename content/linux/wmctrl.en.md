---
author: ['derNiklaas', 'slashleo']
date: 1633404950
title: "wmctrl"
description: "wmctrl, CLI for X Window Manager."
categories: "linux"
---
> More information: <https://manned.org/wmctrl>.

- List all windows, managed by the window manager:

```bash
wmctrl -l
```

- Switch to the first window whose (partial) title matches:

```bash
wmctrl -a window_title
```

- Move a window to the current workspace, raise it and give it focus:

```bash
wmctrl -R window_title
```

- Switch to a workspace:

```bash
wmctrl -s workspace_number
```

- Select a window and toggle fullscreen:

```bash
wmctrl -r window_title -b toggle,fullscreen
```

- Select a window a move it to a workspace:

```bash
wmctrl -r window_title -t workspace_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[slashleo](mailto:37038834+slashleo@users.noreply.github.com) | wmctrl: add page (#4038) | 2020-05-12T18:40:11 | [9aad4459a588](https://github.com/tldr-pages/tldr/commit/9aad4459a58895fac9841b8a7cfc86a809017c15)

