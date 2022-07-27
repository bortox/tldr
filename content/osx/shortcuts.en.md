---
author: ['Victoria Kruczek']
date: 1649985102
title: "shortcuts, TLDR Pages"
description: "shortcuts, Manage shortcuts from the command-line instead of the `Shortcuts` app."
categories: "osx"
---
> More information: <https://support.apple.com/guide/shortcuts-mac/run-shortcuts-from-the-command-line-apd455c82f02/mac>.

- Run the specified shortcut (`Count holidays`):

```bash
shortcuts run "Count holidays"
```

- Print all shortcuts:

```bash
shortcuts list
```

- Print all shortcut folders:

```bash
shortcuts list --folders
```

- Open the specified shortcut (`Count holidays`) in the Shortcuts editor:

```bash
shortcuts view "Count holidays"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Victoria Kruczek](mailto:victoria.kruczek@gmail.com) | shortcuts: add page (#7935) | 2022-04-15T03:11:42 | [0b6c476d2700](https://github.com/tldr-pages/tldr/commit/0b6c476d2700beaef13a9cd57a7fdc1b7f21547b)

