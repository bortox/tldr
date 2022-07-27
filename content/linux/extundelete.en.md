---
author: ['Sawyer Shepherd']
date: 1599611634
title: "extundelete, TLDR Pages"
description: "extundelete, Recover deleted files from ext3 or ext4 partitions by parsing the journal."
categories: "linux"
---
> See also `date` for Unix time information and `umount` for unmounting partitions.

> More information: <http://extundelete.sourceforge.net>.

- Restore all deleted files inside partition N on device X:

```bash
sudo extundelete /dev/sdXN --restore-all
```

- Restore a file from a path relative to root (Do not start the path with `/`):

```bash
extundelete /dev/sdXN --restore-file path/to/file
```

- Restore a directory from a path relative to root (Do not start the path with `/`):

```bash
extundelete /dev/sdXN --restore-directory path/to/directory
```

- Restore all files deleted after January 1st, 2020 (in Unix time):

```bash
extundelete /dev/sdXN --restore-all --after 1577840400
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sawyer Shepherd](mailto:60883209+sawshep@users.noreply.github.com) | extundelete: add page (#4327) | 2020-09-09T02:33:54 | [090ab3fea84a](https://github.com/tldr-pages/tldr/commit/090ab3fea84a39ba965ee24923f0ad1e476ce3f2)

