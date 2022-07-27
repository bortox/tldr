---
author: ['Axel Navarro']
date: 1597839078
title: "konsole, TLDR Pages"
description: "konsole, Konsole: The KDE terminal emulator."
categories: "linux"
---
> More information: <https://konsole.kde.org>.

- Open a new Konsole in a specific directory:

```bash
konsole --workdir path/to/directory
```

- Run a specific command and do not close the window after it exits:

```bash
konsole --noclose -e command
```

- Open a new tab:

```bash
konsole --new-tab
```

- Open a Konsole in the background and bring to the front when Ctrl+Shift+F12 (by default) is pressed:

```bash
konsole --background-mode
```

- Open a Konsole with the emergency FALLBACK profile:

```bash
konsole --fallback-profile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | konsole: add page (#4278) | 2020-08-19T14:11:18 | [44f4a568d96d](https://github.com/tldr-pages/tldr/commit/44f4a568d96d39f4b15850c1f4c0ebce6c370c02)

