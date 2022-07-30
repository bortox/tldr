---
author: ['Phil Ewels', 'Kyle', 'marchersimon']
date: 1638416001
title: "ftp"
description: "ftp, Tools to interact with a server via File Transfer Protocol."
categories: "common"
---
> More information: <https://manned.org/ftp>.

- Connect to an FTP server:

```bash
ftp ftp.example.com
```

- Connect to an FTP server specifying its IP address and port:

```bash
ftp ip_address port
```

- Switch to binary transfer mode (graphics, compressed files, etc):

```bash
binary
```

- Transfer multiple files without prompting for confirmation on every file:

```bash
prompt off
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

- Rename a file on the remote server:

```bash
rename original_filename new_filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ftp: add example to connect via IP (#7502) | 2021-12-02T04:33:21 | [96d26db4658e](https://github.com/tldr-pages/tldr/commit/96d26db4658e8ba7c75fa276a5b009b446976a16)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Phil Ewels](mailto:phil.ewels@scilifelab.se) | ftp: add page (#1173) | 2016-12-13T17:35:47 | [660b0fe51ba4](https://github.com/tldr-pages/tldr/commit/660b0fe51ba4891dcd961f82f39a9443f29eec8b)

