---
author: ['ajs256']
date: 1628520260
title: "circup"
description: "circup, The CircuitPython library updater."
categories: "common"
---
> More information: <https://github.com/adafruit/circup>.

- Interactively update modules on a device:

```bash
circup update
```

- Install a new library:

```bash
circup install library_name
```

- Search for a library:

```bash
circup show partial_name
```

- List all libraries on a connected device in `requirements.txt` format:

```bash
circup freeze
```

- Save all libraries on a connected device in the current directory:

```bash
circup freeze -r
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ajs256](mailto:67526318+ajs256@users.noreply.github.com) | circup: add page (#6293) | 2021-08-09T16:44:20 | [242897dc850b](https://github.com/tldr-pages/tldr/commit/242897dc850b5d7fc01bde0cf46a26d6dba35df2)

