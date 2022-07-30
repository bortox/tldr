---
author: ['Sebastian Staudt']
date: 1633875514
title: "fsutil"
description: "fsutil, Displays information about file system volumes."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/fsutil>.

- Display a list of volumes:

```bash
fsutil volume list
```

- Display information about a volume's file system:

```bash
fsutil fsInfo volumeInfo drive_letter|volume_path
```

- Display the current state of the file system auto-repair for all volumes:

```bash
fsutil repair state
```

- Display the dirty bit state of all volumes:

```bash
fsutil dirty query
```

- Set the dirty bit state of a volume:

```bash
fsutil dirty set drive_letter|volume_path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sebastian Staudt](mailto:koraktor@gmail.com) | fsutil: add page (#6717) | 2021-10-10T16:18:34 | [b80883426901](https://github.com/tldr-pages/tldr/commit/b808834269010e5f19b3bc66fd1adda2aec47757)

