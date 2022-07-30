---
author: ['Axel Navarro']
date: 1595946506
title: "kpackagetool5"
description: "kpackagetool5, KPackage Manager: Install, list, remove Plasma packages."
categories: "linux"
---
> More information: <https://techbase.kde.org/Development/Tutorials/Plasma5/QML2/GettingStarted#Kpackagetool5>.

- List all known package types that can be installed:

```bash
kpackagetool5 --list-types
```

- Install the package from a directory:

```bash
kpackagetool5 --type package_type --install path/to/directory
```

- Update installed package from a directory:

```bash
kpackagetool5 --type package_type --upgrade path/to/directory
```

- List installed plasmoids (--global for all users):

```bash
kpackagetool5 --type Plasma/Applet --list --global
```

- Remove a plasmoid by name:

```bash
kpackagetool5 --type Plasma/Applet --remove "name"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | kpackagetool5: add page (#4213) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-07-28T16:28:26 | [e197e3433661](https://github.com/tldr-pages/tldr/commit/e197e343366196510bf6a1b2355c5e23c2eaa1f3)

