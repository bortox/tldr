---
author: ['nath1as']
date: 1601905448
title: "clamav"
description: "clamav, Open-source anti-virus program."
categories: "linux"
---
> Designed especially for e-mail scanning on mail gateways, but can be used in other contexts.

> More information: <https://www.clamav.net>.

- Update virus definitions:

```bash
freshclam
```

- Scan a file for viruses:

```bash
clamscan path/to/file
```

- Scan directories recursively and print out infected files:

```bash
clamscan --recursive --infected path/to/directory
```

- Scan directories recursively and move them into quarantine:

```bash
clamscan --recursive --move=directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nath1as](mailto:n@th1.as) | clamav: add page (#4423) | 2020-10-05T15:44:08 | [a90277f8f91a](https://github.com/tldr-pages/tldr/commit/a90277f8f91acbafdbb7a63ec788caa56931edf8)

