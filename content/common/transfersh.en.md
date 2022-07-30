---
author: ['marchersimon']
date: 1631937241
title: "transfersh"
description: "transfersh, An unofficial command-line client for transfer.sh."
categories: "common"
---
> More information: <https://github.com/AlpixTM/transfersh>.

- Upload a file to transfer.sh:

```bash
transfersh path/to/file
```

- Upload a file showing a progress bar (requires Python package `requests_toolbelt`):

```bash
transfersh --progress path/to/file
```

- Upload a file using a different file name:

```bash
transfersh --name filename path/to/file
```

- Upload a file to a custom transfer.sh server:

```bash
transfersh --servername upload.server.name path/to/file
```

- Upload all files from a directory recursively:

```bash
transfersh --recursive path/to/directory/
```

- Upload a specific directory as an uncompressed tar:

```bash
transfersh -rt path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | transfersh: add page (#6506) | 2021-09-18T05:54:01 | [30d7e09e0755](https://github.com/tldr-pages/tldr/commit/30d7e09e0755d04108a9b2fc5381e3510cd5f7ce)

