---
author: ['Reinhart Previano Koentjoro']
date: 1634662499
title: "cupsd, TLDR Pages"
description: "cupsd, Server daemon for the CUPS print server."
categories: "common"
---
> More information: <https://www.cups.org/doc/man-cupsd.html>.

- Start `cupsd` in the background, aka. as a daemon:

```bash
cupsd
```

- Start `cupsd` on the [f]oreground:

```bash
cupsd -f
```

- [l]aunch `cupsd` on-demand (commonly used by `launchd` or `systemd`):

```bash
cupsd -l
```

- Start `cupsd` using the specified [`c`]`upsd.conf` configuration file:

```bash
cupsd -c path/to/cupsd.conf
```

- Start `cupsd` using the specified `cups-file`[`s`]`.conf` configuration file:

```bash
cupsd -s path/to/cups-files.conf
```

- [t]est the [`c`]`upsd.conf` configuration file for errors:

```bash
cupsd -t -c path/to/cupsd.conf
```

- [t]est the `cups-file`[`s`]`.conf` configuration file for errors:

```bash
cupsd -t -s path/to/cups-files.conf
```

- Display all available options:

```bash
cupsd -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | cups-config, cupsd, lpinfo: add page (#6623) | 2021-10-19T18:54:59 | [79591fecf696](https://github.com/tldr-pages/tldr/commit/79591fecf696bb2c72db053431f3db6f62bf9231)

