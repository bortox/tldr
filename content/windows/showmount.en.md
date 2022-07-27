---
author: ['Owen Voke']
date: 1570978032
title: "showmount, TLDR Pages"
description: "showmount, Display information about NFS filesystems on Windows Server."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/showmount>.

- Display all exported filesystems:

```bash
showmount -e
```

- Display all NFS clients and their mounted directories:

```bash
showmount -a
```

- Display all NFS mounted directories:

```bash
showmount -d
```

- Display all exported filesystems for a remote server:

```bash
showmount -e server_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | showmount: add page | 2019-10-13T16:47:12 | [761855395652](https://github.com/tldr-pages/tldr/commit/761855395652e0595c189ca71546534bdc46cd16)

