---
author: ['Jeroen Meulemeester', 'Lucas Gabriel Schneider']
date: 1629110041
title: "microcom"
description: "microcom, A minimalistic terminal program, used to access remote devices via a serial, CAN or telnet connection from the console."
categories: "linux"
---
> More information: <https://manned.org/microcom>.

- Open a serial port using the specified baud rate:

```bash
microcom --port path/to/serial_port --speed baud_rate
```

- Establish a telnet connection to the specified host:

```bash
microcom --telnet hostname:port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | microcom: Fix various review comments - Expand the description to prevent confusion - Use 'baud rate' instead of baudrate - Replace [...] | 2017-10-12T00:12:15 | [94e2496c296d](https://github.com/tldr-pages/tldr/commit/94e2496c296da600e9afa660acb96e817ce2465d)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | microcom: add page | 2017-10-09T23:04:52 | [d9243947c526](https://github.com/tldr-pages/tldr/commit/d9243947c526a03da6054202f0a2b99e8a5ba3dc)

