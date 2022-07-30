---
author: ['Seth Falco']
date: 1647863281
title: "gnome-software"
description: "gnome-software, Add and remove applications and update your system."
categories: "linux"
---
> More information: <https://apps.gnome.org/app/org.gnome.Software/>.

- Launch the GNOME Software GUI if it's not already running:

```bash
gnome-software
```

- Launch the GNOME Software GUI if it's not open, and navigate to the specified page:

```bash
gnome-software --mode updates|updated|installed|overview
```

- Launch the GNOME Software GUI if it's not open, and view the specified package:

```bash
gnome-software --details package_name
```

- Display the version:

```bash
gnome-software --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | gnome-software: add page (#7917) | 2022-03-21T12:48:01 | [d8327bb073ab](https://github.com/tldr-pages/tldr/commit/d8327bb073abeaac759b79e526cec64a25ab65e9)

