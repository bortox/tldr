---
author: ['marchersimon', 'Starbeamrainbowlabs']
date: 1622480790
title: "xfce4-terminal, TLDR Pages"
description: "xfce4-terminal, The XFCE4 terminal emulator."
categories: "linux"
---
> More information: <https://docs.xfce.org/apps/xfce4-terminal/start>.

- Open a new terminal window:

```bash
xfce4-terminal
```

- Set the initial title:

```bash
xfce4-terminal --initial-title "initial_title"
```

- Open a new tab in the current terminal window:

```bash
xfce4-terminal --tab
```

- Execute a command in a new terminal window:

```bash
xfce4-terminal --command "command_with_args"
```

- Keep the terminal around after the executed command finishes executing:

```bash
xfce4-terminal --command "command_with_args" --hold
```

- Open multiple new tabs, executing a command in each:

```bash
xfce4-terminal --tab --command "command_a" --tab --command "command_b"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xfce4-screenshooter, xfce4-terminal: add link (#6075) | 2021-05-31T19:06:30 | [cfd0b5bd34da](https://github.com/tldr-pages/tldr/commit/cfd0b5bd34da972d7780b0b8580b3fb2af145607)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | xfce4-terminal: add page (#2548) | 2018-11-05T23:36:48 | [99d08c8d1022](https://github.com/tldr-pages/tldr/commit/99d08c8d10222d87369d4090c532bb8d2e8d4c17)

