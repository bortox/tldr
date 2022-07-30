---
author: ['marchersimon']
date: 1630864738
title: "tlmgr gui"
description: "tlmgr gui, Start a graphical user interface for `tlmgr`."
categories: "common"
---
> `tlmgr gui` depends on the package `perl-tk`, which has to be installed manually.

> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Start a GUI for `tlmgr`:

```bash
sudo tlmgr gui
```

- Start a GUI specifying the background color:

```bash
sudo tlmgr gui -background "#f39bc3"
```

- Start a GUI specifying the foreground color:

```bash
sudo tlmgr gui -foreground "#0ef3bd"
```

- Start a GUI specifying the font and font size:

```bash
sudo tlmgr gui -font "helvetica 18"
```

- Start a GUI setting a specific geometry:

```bash
sudo tlmgr gui -geometry widthxheight-xpos+ypos
```

- Start a GUI passing an arbitrary X resource string:

```bash
sudo tlmgr gui -xrm xresource
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-gui: add page (#6467) | 2021-09-05T19:58:58 | [bbefc7758298](https://github.com/tldr-pages/tldr/commit/bbefc7758298d240b22ebf03d05606c5ac358966)

