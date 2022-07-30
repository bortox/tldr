---
author: ['Jay Piamjariyakul']
date: 1602508023
title: "chkdsk"
description: "chkdsk, Check file system and volume metadata for errors."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/chkdsk>.

- Specify the drive letter (followed by a colon), mount point, or volume name to check:

```bash
chkdsk volume
```

- Fix errors on a specific volume:

```bash
chkdsk volume /f
```

- Dismount a specific volume before checking:

```bash
chkdsk volume /x
```

- Change the log file size to the specified size (only for NTFS):

```bash
chkdsk /lsize
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jay Piamjariyakul](mailto:j.piamjariyakul@outlook.com) | chkdsk: add page (#4657) | 2020-10-12T15:07:03 | [44cdd2786902](https://github.com/tldr-pages/tldr/commit/44cdd278690244fe81361d11ce4b25cb23728a83)

