---
author: ['Axel Navarro']
date: 1614172555
title: "balooctl"
description: "balooctl, File indexing and searching framework for KDE Plasma."
categories: "linux"
---
> More information: <https://wiki.archlinux.org/index.php/Baloo>.

- Display help:

```bash
balooctl
```

- Display the status of the indexer:

```bash
balooctl status
```

- Enable/Disable the file indexer:

```bash
balooctl enable|disable
```

- Clean the index database:

```bash
balooctl purge
```

- Suspend the file indexer:

```bash
balooctl suspend
```

- Resume the file indexer:

```bash
balooctl resume
```

- Display the disk space used by Baloo:

```bash
balooctl indexSize
```

- Check for any unindexed files and index them:

```bash
balooctl check
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | balooctl: add page (#5291) | 2021-02-24T14:15:55 | [8db0a074e71a](https://github.com/tldr-pages/tldr/commit/8db0a074e71a1599ea19e93372d7e0b3bb6fc76b)

