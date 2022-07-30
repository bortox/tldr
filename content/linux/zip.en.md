---
author: ['Emily Grace Seville']
date: 1657140467
title: "zip"
description: "zip, Package and compress (archive) files into zip file."
categories: "linux"
---
> See also: `unzip`.

> More information: <https://manned.org/zip>.

- Add files/directories to a specific archive:

```bash
zip -r path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Remove files/directories from a specific archive:

```bash
zip --delete path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Archive files/directories e[x]cluding specified ones:

```bash
zip path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ... --exclude path/to/excluded_files_or_directories
```

- Archive files/directories with a specific compression level (`0` - the lowest, `9` - the highest):

```bash
zip -r -0-9 path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Create an encrypted archive with a specific password:

```bash
zip -r --encrypt path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Archive files/directories to a multi-part [s]plit zip file (e.g. 3 GB parts):

```bash
zip -r -s 3g path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Print a specific archive contents:

```bash
zip -sf path/to/compressed.zip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | zip: add/refresh pages (#7996) | 2022-07-06T22:47:47 | [5e2f4072bce4](https://github.com/tldr-pages/tldr/commit/5e2f4072bce4e1bb1ffc80edd5d5ec223042182a)

