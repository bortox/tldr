---
author: ['Rahmanu Hermawan']
date: 1640861732
title: "minicom"
description: "minicom, A program to communicate with the serial interface of a device."
categories: "linux"
---
> More information: <https://manned.org/minicom>.

- Open a given serial port:

```bash
sudo minicom --device /dev/ttyUSB0
```

- Open a given serial port with a given baud rate:

```bash
sudo minicom --device /dev/ttyUSB0 --baudrate 115200
```

- Enter the configuration menu before communicating with a given serial port:

```bash
sudo minicom --device /dev/ttyUSB0 --setup
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rahmanu Hermawan](mailto:rahmanuh@pasdirumah.site) | minicom: add page (#7564) | 2021-12-30T11:55:32 | [6a5c49c3242c](https://github.com/tldr-pages/tldr/commit/6a5c49c3242c7ecdfa7d44360967aada36a73752)

