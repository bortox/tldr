---
author: ['Owen Voke']
date: 1609243325
title: "ftp"
description: "ftp, Interactively transfer files between a local and remote FTP server."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/ftp>.

- Connect to a remote FTP server interactively:

```bash
ftp host
```

- Log in as an anonymous user:

```bash
ftp -A host
```

- Disable automatic login upon initial connection:

```bash
ftp -n host
```

- Run a file containing a list of FTP commands:

```bash
ftp -s:path/to/file host
```

- Download multiple files (glob expression):

```bash
mget *.png
```

- Upload multiple files (glob expression):

```bash
mput *.zip
```

- Delete multiple files on the remote server:

```bash
mdelete *.txt
```

- Display detailed help:

```bash
ftp --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | ftp: add more information link | 2020-12-29T13:02:05 | [0c16eb24fd35](https://github.com/tldr-pages/tldr/commit/0c16eb24fd351c0a5e08795585cbedbdbf63d32a)
[Owen Voke](mailto:owzie123@gmail.com) | ftp: add page (#2157) | 2018-06-28T15:14:55 | [15f27a6a12a1](https://github.com/tldr-pages/tldr/commit/15f27a6a12a1b848696118fe0d521082f0f27ffc)

