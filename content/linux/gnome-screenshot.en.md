---
author: ['kai', 'Seth Falco']
date: 1656212615
title: "gnome-screenshot"
description: "gnome-screenshot, Capture the screen, a window, or a user-defined area and save the image to a file."
categories: "linux"
---
> More information: <https://manned.org/gnome-screenshot>.

- Take a screenshot and save it to the default location, normally `~/Pictures`:

```bash
gnome-screenshot
```

- Take a screenshot and save it to the named file location:

```bash
gnome-screenshot --file path/to/file
```

- Take a screenshot and save it to the clipboard:

```bash
gnome-screenshot --clipboard
```

- Take a screenshot after the specified number of seconds:

```bash
gnome-screenshot --delay 5
```

- Launch the GNOME Screenshot GUI:

```bash
gnome-screenshot --interactive
```

- Take a screenshot of the current window and save it to the specified file location:

```bash
gnome-screenshot --window --file path/to/file
```

- Take a screenshot after the specified number of seconds and save it to the clipboard:

```bash
gnome-screenshot --delay 10 --clipboard
```

- Display the version:

```bash
gnome-screenshot --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kai](mailto:gmdezreal@gmail.com) | gnome-screenshot: fix link (#8153) | 2022-06-26T05:03:35 | [56d6c3f0bca1](https://github.com/tldr-pages/tldr/commit/56d6c3f0bca16f5468bcf4d1884df166ad235518)
[Seth Falco](mailto:seth@falco.fun) | gnome-screenshot: add page (#7916) | 2022-03-23T14:14:10 | [da24d7dbe065](https://github.com/tldr-pages/tldr/commit/da24d7dbe0655a19160d459e7af5a5080993a82e)

