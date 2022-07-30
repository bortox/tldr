---
author: ['Owen Voke']
date: 1573306061
title: "mount"
description: "mount, Mount Network File System (NFS) network shares."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/mount>.

- Mount a share to the "Z" drive letter:

```bash
mount \\computer_name\share_name Z:
```

- Mount a share to the next available drive letter:

```bash
mount \\computer_name\share_name *
```

- Mount a share with a read timeout in seconds (defaults to 0.8, can be 0.9 or 1 to 60):

```bash
mount -o timeout=seconds \\computer_name\share_name Z:
```

- Mount a share and retry up to 10 times if it fails:

```bash
mount -o retry=retries \\computer_name\share_name Z:
```

- Mount a share with forced case sensitivity:

```bash
mount -o casesensitive \\computer_name\share_name Z:
```

- Mount a share as an anonymous user:

```bash
mount -o anon \\computer_name\share_name Z:
```

- Mount a share using a specific mount type:

```bash
mount -o mtype=soft|hard \\computer_name\share_name Z:
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | mount: add page (#3530) | 2019-11-09T14:27:41 | [3e6b16bb2d29](https://github.com/tldr-pages/tldr/commit/3e6b16bb2d2968adde14a5bda4f78c026cea9913)

