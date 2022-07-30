---
author: ['marchersimon']
date: 1637961256
title: "install-tl"
description: "install-tl, TeX Live cross-platform installer."
categories: "common"
---
> More information: <https://tug.org/texlive/>.

- Start the text-based installer (default on Unix systems):

```bash
install-tl -no-gui
```

- Start the GUI installer (default on macOS and Windows, requires Tcl/Tk):

```bash
install-tl -gui
```

- Install TeX Live as defined in a specific profile file:

```bash
install-tl -profile path/to/texlive.profile
```

- Start the installer with the settings from a specific profile file:

```bash
install-tl -init-from-file path/to/texlive.profile
```

- Start the installer for installation on a portable device, like a USB stick:

```bash
install-tl -portable
```

- Show help for `install-tl`:

```bash
install-tl -help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | install-tl: add page (#7434) | 2021-11-26T22:14:16 | [372cc4144b5f](https://github.com/tldr-pages/tldr/commit/372cc4144b5fbe3e2cdb49a2aee2221b60294915)

