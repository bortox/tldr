---
author: ['Alex Treichler']
date: 1651011817
title: "dumpcap"
description: "dumpcap, A network traffic dump tool."
categories: "common"
---
> More information: <https://www.wireshark.org/docs/man-pages/dumpcap.html>.

- Display available interfaces:

```bash
dumpcap --list-interfaces
```

- Capture packets on a specific interface:

```bash
dumpcap --interface 1
```

- Capture packets to a specific location:

```bash
dumpcap --interface 1 -w path/to/output_file.pcapng
```

- Write to a ring buffer with a specific max file limit of a specific size:

```bash
dumpcap --interface 1 -w path/to/output_file.pcapng --ring-buffer filesize:500000 --ring-buffer files:10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex Treichler](mailto:alex.trei@gmail.com) | dumpcap: add page (#8042) | 2022-04-27T00:23:37 | [3c3151469158](https://github.com/tldr-pages/tldr/commit/3c31514691580d8692eeadea83023b1eabd3227d)

