---
author: ['Florian B']
date: 1619636220
title: "qutebrowser, TLDR Pages"
description: "qutebrowser, A keyboard-driven, vim-like browser based on PyQt5."
categories: "common"
---
> More information: <https://qutebrowser.org/>.

- Open qutebrowser with a specified storage directory:

```bash
qutebrowser --basedir path/to/directory
```

- Open a qutebrowser instance with temporary settings:

```bash
qutebrowser --set content.geolocation true|false
```

- Restore a named session of a qutebrowser instance:

```bash
qutebrowser --restore session_name
```

- Launch qutebrowser, opening all URLs using the specified method:

```bash
qutebrowser --target auto|tab|tab-bg|tab-silent|tab-bg-silent|window|private-window
```

- Open qutebrowser with a temporary base directory and print logs to stdout as JSON:

```bash
qutebrowser --temp-basedir --json-logging
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | qutebrowser: add page (#5850) | 2021-04-28T20:57:00 | [d3f8cd8bae98](https://github.com/tldr-pages/tldr/commit/d3f8cd8bae989078eebe1120931656186422a6a2)

