---
author: ['Peter Tripp', 'bl-ue', 'Emily Grace Seville']
date: 1644837703
title: "pkgutil"
description: "pkgutil, Query and manipulate Mac OS X Installer packages and receipts."
categories: "osx"
---
> More information: <https://ss64.com/osx/pkgutil.html>.

- List package IDs for all installed packages:

```bash
pkgutil --pkgs
```

- Verify cryptographic signatures of a package file:

```bash
pkgutil --check-signature path/to/filename.pkg
```

- List all the files for an installed package given its ID:

```bash
pkgutil --files com.microsoft.Word
```

- Extract the contents of a package file into a directory:

```bash
pkgutil --expand-full path/to/filename.pkg path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Peter Tripp](mailto:petertripp@gmail.com) | pkgutil: add --expand-full (#4208) | 2020-08-10T01:26:40 | [8a5d05ba8b94](https://github.com/tldr-pages/tldr/commit/8a5d05ba8b94a5f24127fac209d8f2e1c96ffd4c)
[Peter Tripp](mailto:petertripp@gmail.com) | pkgutil: add page (osx) (#3755) | 2020-01-21T13:17:11 | [050891747e3f](https://github.com/tldr-pages/tldr/commit/050891747e3f0d72848a6369a72483f9d07c0c5c)

