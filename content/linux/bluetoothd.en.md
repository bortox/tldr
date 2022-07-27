---
author: ['Axel Navarro']
date: 1624651554
title: "bluetoothd, TLDR Pages"
description: "bluetoothd, Daemon to manage bluetooth devices."
categories: "linux"
---
> More information: <https://manned.org/bluetoothd>.

- Start the daemon:

```bash
bluetoothd
```

- Start the daemon, logging to stdout:

```bash
bluetoothd --nodetach
```

- Start the daemon with a specific configuration file (defaults to `/etc/bluetooth/main.conf`):

```bash
bluetoothd --configfile path/to/file
```

- Start the daemon with verbose output to stderr:

```bash
bluetoothd --debug
```

- Start the daemon with verbose output coming from specific files in the bluetoothd or plugins source:

```bash
bluetoothd --debug=path/to/file1:path/to/file2:path/to/file3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | bluetoothd: add page (#6158) | 2021-06-25T22:05:54 | [85d860847881](https://github.com/tldr-pages/tldr/commit/85d8608478815aeb38888b3658632832e1710f9e)

