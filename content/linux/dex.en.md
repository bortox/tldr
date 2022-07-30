---
author: ['Florian B']
date: 1618598798
title: "dex"
description: "dex, DesktopEntry Execution is a program to generate and execute DesktopEntry files of the Application type."
categories: "linux"
---
> More information: <https://github.com/jceb/dex>.

- Execute all programs in the autostart folders:

```bash
dex --autostart
```

- Execute all programs in the specified folders:

```bash
dex --autostart --search-paths path/to/directory1:path/to/directory2:path/to/directory3:
```

- Preview the programs would be executed in a GNOME specific autostart:

```bash
dex --autostart --environment GNOME
```

- Preview the programs would be executed in a regular autostart:

```bash
dex --autostart --dry-run
```

- Preview the value of the DesktopEntry property `Name`:

```bash
dex --property Name path/to/file.desktop
```

- Create a DesktopEntry for a program in the current directory:

```bash
dex --create path/to/file.desktop
```

- Execute a single program (with `Terminal=true` in the desktop file) in the given terminal:

```bash
dex --term terminal path/to/file.desktop
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | dex: add page (#5752) | 2021-04-16T20:46:38 | [01c4497b4f2e](https://github.com/tldr-pages/tldr/commit/01c4497b4f2e324229fcdafecde212375aec487a)

