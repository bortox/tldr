---
author: ['marchersimon']
date: 1618754946
title: "pio debug, TLDR Pages"
description: "pio debug, Debug PlatformIO projects."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_debug.html>.

- Debug the PlatformIO project in the current directory:

```bash
pio debug
```

- Debug a specific PlatformIO project:

```bash
pio debug --project-dir path/to/platformio_project
```

- Debug a specific environment:

```bash
pio debug --environment environment
```

- Debug a PlatformIO project using a specific configuration file:

```bash
pio debug --project-conf path/to/platformio.ini
```

- Debug a PlatformIO project using the `gdb` debugger:

```bash
pio debug --interface=gdb gdb_options
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-debug, piodebuggdb: add page (#5780) * pio-debug, piodebuggdb: add page * Apply suggestion from code review Co-authored-by: bl-ue [...] | 2021-04-18T16:09:06 | [6b9e894deee0](https://github.com/tldr-pages/tldr/commit/6b9e894deee06ba9f6e48f1a319004c8d834d02b)

