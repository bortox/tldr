---
author: ['sawshep']
date: 1612040850
title: "smbget"
description: "smbget, `wget`-like utility for downloading files from SMB servers."
categories: "linux"
---
> More information: <https://www.samba.org/samba/docs/current/man-html/smbget.1.html>.

- Download a file from a server:

```bash
smbget smb://server/share/file
```

- Download a share or directory recursively:

```bash
smbget --recursive smb://server/share
```

- Connect with a username and password:

```bash
smbget smb://server/share/file --user username%password
```

- Require encrypted transfers:

```bash
smbget smb://server/share/file --encrypt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sawshep](mailto:60883209+sawshep@users.noreply.github.com) | smbget: add page (#5187) | 2021-01-30T22:07:30 | [0b8670109ee0](https://github.com/tldr-pages/tldr/commit/0b8670109ee0efe7ec01752cc4e0e277ba169a6b)

