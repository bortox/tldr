---
author: ['ciph3rz']
date: 1637493575
title: "smbmap"
description: "smbmap, Allow users to enumerate samba share drives across an entire domain."
categories: "common"
---
> More information: <https://github.com/ShawnDEvans/smbmap>.

- Enumerate hosts with NULL sessions enabled and open shares:

```bash
smbmap --host-file path/to/file
```

- Enumerate hosts and check SMB file permissions:

```bash
smbmap --host-file path/to/file -u username -p password -q
```

- Connect to an ip or hostname through smb using a username and password:

```bash
smbmap -u username -p password -d domain -H ip_or_hostname
```

- Locate and download files [R]ecursively up to N levels depth, searching for filename pattern (regex), and excluding certain shares:

```bash
smbmap --host-file path/to/file -u username -p password -q -R --depth number --exclude sharename -A filepattern
```

- Upload file through smb using username and password:

```bash
smbmap -u username -p password -d domain -H ip_or_hostname --upload path/to/file '/share_name/remote_filename'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ciph3rz](mailto:46655414+ciph3rz@users.noreply.github.com) | smbmap: add page (#7053) | 2021-11-21T12:19:35 | [da2545ca5415](https://github.com/tldr-pages/tldr/commit/da2545ca54151e451f4d4e0e892bf5d858c06fe2)

