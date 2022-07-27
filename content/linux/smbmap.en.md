---
author: ['Alex']
date: 1603541107
title: "smbmap, TLDR Pages"
description: "smbmap, SMB enumeration tool."
categories: "linux"
---
> More information: <https://github.com/ShawnDEvans/smbmap>.

- Display SMB shares and permissions on a host, prompting for user's password or NTLM hash:

```bash
smbmap -u username --prompt -H ip
```

- Display SMB shares and permissions on a host, specifying the domain and passing the password NTLM hash:

```bash
smbmap -u username --prompt -d domain -H ip
```

- Display SMB shares and list a single level of directories and files:

```bash
smbmap -u username --prompt -H ip -r
```

- Display SMB shares and recursively list a defined number of levels of directories and files:

```bash
smbmap -u username --prompt -H ip -R --depth 3
```

- Display SMB shares and recursively list directories and files, downloading the files matching a regular expression:

```bash
smbmap -u username --prompt -H ip -R -A pattern
```

- Display SMB shares and recursively list directories and files, searching for file content matching a regular expression:

```bash
smbmap -u username --prompt -H ip -R -F pattern
```

- Execute a shell command on a remote system:

```bash
smbmap -u username --prompt -H ip -x command
```

- Upload a file to a remote system:

```bash
smbmap -u username --prompt -H ip --upload source destination
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | smbmap: add page (#4749) | 2020-10-24T14:05:07 | [622e1cf73cea](https://github.com/tldr-pages/tldr/commit/622e1cf73cea3d9baee413447d155c7dd68ebef6)

