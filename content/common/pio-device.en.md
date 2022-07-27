---
author: ['bl-ue', 'marchersimon']
date: 1621541621
title: "pio device, TLDR Pages"
description: "pio device, Manage and monitor PlatformIO devices."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/device/>.

- List all available serial ports:

```bash
pio device list
```

- List all available logical devices:

```bash
pio device list --logical
```

- Start an interactive device monitor:

```bash
pio device monitor
```

- Start an interactive device monitor and listen to a specific port:

```bash
pio device monitor --port /dev/ttyUSBX
```

- Start an interactive device monitor and set a specific baud rate (defaults to 9600):

```bash
pio device monitor --baud 57600
```

- Start an interactive device monitor and set a specific EOL character (defaults to `CRLF`):

```bash
pio device monitor --eol CRLF|CR|LF
```

- Go to the menu of the interactive device monitor:

```bash
Ctrl + T
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-device: add page (#5725) | 2021-04-10T21:20:32 | [00f46c3dc0af](https://github.com/tldr-pages/tldr/commit/00f46c3dc0af7ad92626aa5dabfae31389cd9c00)

