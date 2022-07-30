---
author: ['Sarah Haïm-Lubczanski', 'Owen Voke']
date: 1635887488
title: "phar"
description: "phar, Create, update or extract PHP archives (PHAR)."
categories: "linux"
---
> More information: <https://manned.org/phar>.

- Add space-separated files or directories to a Phar file:

```bash
phar add -f path/to/phar_file files_or_directories
```

- Display the contents of a Phar file:

```bash
phar list -f path/to/phar_file
```

- Delete the specified file or directory from a Phar file:

```bash
phar delete -f path/to/phar_file -e file_or_directory
```

- Display full usage information and available hashing/compression algorithms:

```bash
phar help
```

- Compress or uncompress files and directories in a Phar file:

```bash
phar compress -f path/to/phar_file -c algorithm
```

- Get information about a Phar file:

```bash
phar info -f path/to/phar_file
```

- Sign a Phar file with a specific hash algorithm:

```bash
phar sign -f path/to/phar_file -h algorithm
```

- Sign a Phar file with an OpenSSL private key:

```bash
phar sign -f path/to/phar_file -h openssl -y path/to/private_key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | phar: add more information link (#7322) | 2021-11-02T22:11:28 | [e11370e25eab](https://github.com/tldr-pages/tldr/commit/e11370e25eaba72fd6546633e120e066024abe47)
[Owen Voke](mailto:owzie123@gmail.com) | phar: add page (#2000) | 2018-03-06T10:52:41 | [f8217329885b](https://github.com/tldr-pages/tldr/commit/f8217329885bbd6aaa46af42b72026d3561888e8)

